# Matomo PasswordVerifier Plugin

## Description

This plugin sends the first 5 characters of the SHA1 hash of the password to the [haveibeenpwned.com database](https://haveibeenpwned.com/Passwords) of over 500 million passwords exposed in data breaches. If the password is found, Matomo rejects it and asks the user to use a more secure password.

This plugin only acts on passwords changes and can't access existing passwords as they are stored securely hashed by Matomo.
