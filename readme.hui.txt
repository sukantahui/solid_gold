✅ Step-by-step: Set a global Bearer Token

    Click on the Environment Icon (top left next to your workspace name).

    Choose "Manage Environments".

    In the base environment, add your token like this:
{
  "auth": {
    "bearerToken": "your-token-here"
  }
}

In each request's Auth tab:

    Set the type to Bearer Token.

    For the token value, use: {{ auth.bearerToken }}
