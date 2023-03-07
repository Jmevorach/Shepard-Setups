Testing setup for Shepard.

Infrastructure configruation can be found [here](https://github.com/Jmevorach/Shepard-Setups/blob/main/testing-setup/infrastructure/cdk.json).

The script run by this setup can be found [here](https://github.com/Jmevorach/Shepard-Setups/blob/main/testing-setup/code/testing_code.py).

Running the test payload in the "error" folder in the "test_payloads" folder will result in an error and not produce any output zipfiles.

Running the test payload in the "no_tags_no_error" folder in the "test_payloads" folder will result in the creation of one or more output zipfiles with no tags appended as a prefix to the output zipfile names.

Running the test payload in the "tag_no_error" folder in the "test_payloads" folder will result in the creation of one or more output zipfiles with a tag of "test_file" appended as a prefix to the output zipfile names.

The "test_secrets" folder in this repository can be used to experiment with the "shepard secretify" command. 

Because the testing code this setup runs copies the entire contents of "ROOT_INPUT_NAME" to the directory at "ROOT_OUTPUT_NAME" you're able to see the entire contents of any secrets folder generated from any secrets deployed to this architecture. 
