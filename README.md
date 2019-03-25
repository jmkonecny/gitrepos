# Github Repository Cloner
Clones all repositories from the specified GitHub organization or user.

## Usage
- Requires *Python 3.X*
- Usage: <code>gitrepos <username> [options]</code>
  - <code>-p</code>:  process only the first page of repos
  - <code>-u</code>:  process the given username as a user [default: organization]
  - <code>-n</code>:  skips token-based authentication
  - <code>-l</code>:  lists all repositories without cloning
  - <code>-d <directory></code>:  clones repositories to the given directory
