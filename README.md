# OpenVPN3 Bash Scripts for Sanity

Just a wrapper to automate frequently used OpenVPN3 operations on Linux, including logging in with a stored password and handling of MFA prompts. This script currently uses the Ubuntu Keyring as its credentials store, so it's restricted to installations that have keyrings accessible by the secret-tool utility.

# Requirements

Ensure that the following packages are installed (e.g. via apt)

- openvpn3
- libsecret-tools
