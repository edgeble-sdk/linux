.. _link_token:

Github Docker Registry
======================

- Generate a Personal Access Token (PAT):
  ::
 
    Go to your GitHub account settings.
    Navigate to "Developer settings" > "Personal access tokens." > "Tokens(classic)"
    Generate a new token with the write:packages scope.
    Copy the generated token.

- Login Docker Registry:
  
   ::

    export CR_PAT=<YOUR_TOEKN>
    echo $CR_PAT | sudo docker login ghcr.io -u USERNAME --password-stdin
