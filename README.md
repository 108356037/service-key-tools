## Service key tools

This repo contains the necessary tools to create service key.
For the executable binaries, below is their sha256 checksum:

**tinkey：**
`6f6380c2d124eca3214adb370f59eb936d8e77c344919520bfb70c2d91445680`

**tinkey_deploy.jar：**
`42e8cbb2b09833886ffdc0d1ff92fbb57a07d35cc95dad56cb8142063a3caa0b`

**shamir：**
`74468fc082019478f96320717c594c106f753c578bd70aec2f9e864e3bacf678`

## Public Key

`keys` folder contains a public key downloaded from GCP.
++**Please encrypt**++ the service key with this public key before uploading to any vault.

## About Shamir

The shamir executable binary is built from this repo:
https://github.com/108356037/go-shamir

## Licenses

We use the MIT by default, it depends on your dependencies, but be careful not to use the GPL or its associated licenses.
