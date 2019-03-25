# Github Repository Cloner
Clones all repositories from the specified GitHub organization or user.

## Usage
- Requires Python 3.X
- Usage: <code>gitrepos <username> [options]</code>
  - -p:  process only the first page of repos
  - -u:  process the given username as a user [default: organization]
  - -n:  skips token-based authentication
  - -l:  lists all repositories without cloning
  - -d <directory>:  clones repositories to the given directory
