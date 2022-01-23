# CLI-jfrog-API
Project for Jfrog API
made by Itay Rotman
cli-jfrog - a CLI for Jfrog API with few commands

Commands:
  -p|--ping             Get server connection status (example: OK)
  -V|--version          Get Artifactory version
  --create-user         Create user in artifactory (require Pro subscription) example: ./cli-jfrog --create-user testuser1
  --delete-user         Delete user in artifactory (require Pro subscription) example: ./cli-jfrog --delete-user testuser1
  -df|--storage-info    Returns storage summary information regarding binaries, file store and repositories.
  --create-repo         Creates a new repository in Artifactory with the provided configuration. (require Pro subscription) example: ./cli-jfrog --create-repo REPOKEY
  --update-repo         Updates an existing repository configuration in Artifactory with the provided configuration elements. (require Pro subscription) example: ./cli-jfrog --update-repo REPOKEY
  --get-repo            Returns a list of minimal repository details for all repositories of the specified type, you can choose type and packagetype or leave blank.
  *                     Help
