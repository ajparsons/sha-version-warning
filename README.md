# Sha Version Warning

Version: 1.0.0



Github Action to raise a warning if an action is not being referred to by SHA

## Usage

```yaml

# It is better practice to use the SHA hash of this tag rather than the tag itself.
- uses: ajparsons/sha-version-warning@v1
  id: example-step 
  with:
    action_path: '' 

```


## Inputs

### action_path



Path to action being checked.






## Outputs

### warning_given

Boolean if there warning was raised. Will be none if 'commit_and_push' was false.


