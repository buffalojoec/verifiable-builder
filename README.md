# Verifiable Builder

A simple repository for producing verifiable builds of solana programs.

Example:
```shell
anchor build --verifiable --program-name spl_name_service --solana-version 1.16.3 --docker-image backpackapp/build:v0.28.0 --arch sbf
```

Verifiably-built program binary will be output to `target/verifiable/program_name.so`.

Mac users: https://stackoverflow.com/a/76586216/19949857