**echo**: takes one string argument and prints it to the shell window.

eg. echo 'Hello World'

#### List contents
  
  - **ls**: lists contents present in the current directory.
  
  eg. ls

  - **ls -l**: works same way as 'ls' but provides more details about files and directories.
  
  eg. ls -l

  - **ls -lh**: works same way as 'ls -l' while providing details in human readable format.
  
  eg. ls -lh

**pwd**: shows what the present working directory is.

eg. pwd

#### Moving, Copying and Creating files and directories

  - **mv**: moves file or directory from source to destination.
  
  eg. mv file1.txt example_dir/file1.txt
  eg. mv file1.txt example_dir/
  
  Above two commands work the same way when moving files or directories in an already existing directory example_dir.
  
  - **cp**:

  - **nano**:
  
  - **mkdir**: creates a new directory with the name provided as argument.
  
  eg. mkdir new_dir1
  
  - **mkdir -p**: creates directory inside another directory when parent directory doesn't exist.
  
  eg. mkdir -p new_dir2/new_dir3 (creates dir2 and dir3 inside dir2 without having to use the command twice)

#### Deleting files and directories

  - **rm**: permanently deletes files (use with caution, you cannot undo).
  
  eg. rm file1.txt (deletes file1.txt file ***permanently***)
  
  - **rm -R**: permanently deletes directories (use with caution, you cannot undo).
  
  eg. rm -R dir1 (deletes dir1 directory ***permanently***)
