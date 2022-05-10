# Google Cloud Authentication for Insomnia

Shameless borrowed from https://github.com/nawhi/insomnia-plugin-cloud-run-auth, but uses `gcloud auth print-access-token` to generate an access token rather than an identity token.

# Usage

Ensure you have installed the Google Cloud SDK and its bundled gcloud command-line interface.

Create a Bearer Token authentication and add the "Google Cloud Access Token" template tag as the token value.

The settings specify a default path to the gcloud executable of ~/google-cloud-sdk/bin. If it is somewhere else on your machine you may need to change it.