# 1.0.0-rc

This is a fork of [leocavalcante/encrypt](https://github.com/leocavalcante/encrypt), which I created for my own needs since the project does not seem to be maintained anymore. Initial release 1.0.0 will reset the versioning, since the repo is renamed to highlight the main difference: the core library pointycastle has changed its repo to pc-dart and needed to be updated, hence encrypt_pc. The previous changelong is kept for now since the repo has barely changed. Initial release changes are therefore minimal:

- Upgrade dependency `lints` to `5.1.1`
- Upgrade dependency `pointycastle` to `4.0.0`
- No breaking changes to the API

**I welcome any contributors who are interested in the project, I am not a cryptography specialist in any way, so the project would need maintainers with relevant experience or deeper understanding of cryptography** Thanks for checking out this repo, feel free to contact me.

# 5.0.4

- Force Pointycastle version

# 5.0.3

- Fixed tests failing with AES ECB with padding by @JimWuerch in #312
- fix: Could not parse version "~3.6.2" by @Marc-R2 in #315

# 5.0.2

- Update pointycastle version to support AES-GCM with Flutter Web
- Support AES-GCM
- Fixed null safety related warnings from `package:asnlib`.

# 5.0.1

- Fix web support

# 5.0.0

- Null safety support stable (sdk: ">=2.12.0 <3.0.0")

# 5.0.0-beta.1

- Preview/prerelase null safety support

# 4.1.0

- PointyCastle v2

# 4.0.3

- Fix UTF-8 conversion on Fernet keys.

# 4.0.2

- Fix streamble AES modes without padding.

# 4.0.1

- Upgrade dependencies.

# 4.0.0

- Digital signatures signing and verification.

# 3.3.1

- Move I/O helper to another lib

# 3.3.0

- Added the Fernet algorithm, thanks to [@timfeirg](https://github.com/timfeirg)
- Moved the secure random logic to the lib
- Added key stretching

# 3.2.0

- Fix wrong casting.
- Add decryptBytes, avoids UTF-8 high coupling.
- Add public decryption and private encryption for digital signature verification.

# 3.1.0

- Add support for CRLF PEM keys.
- Fix AES without padding.
- Add `encryptBytes` method.

# 3.0.0

- Enforce IV uniqueness.

# 2.2.0

- AES padding is now optional with defaults to PKCS7.

# 2.1.0

- `secure-random` command-line tool.

# 2.0.0

- All new API

# 1.0.1

- RSA

# 1.0.0

- Stable and documented API

# 0.2.0+2

- Remove unnecessary `new`s
- Improve static typing
- Add examples index (README)

# 0.2.0+1

- Refresh dependencies, make sure it works on Dart 2
