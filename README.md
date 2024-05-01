# Cipher Files Internationalization

Welcome to the Internationalization (i18n) repository for [**Cipher Files**](https://cipherfiles.com/)!
This repository contains translations for our project into various languages. We appreciate your interest in contributing to make our project more accessible to global audiences.

## Contributing

### Getting Started

1. **Fork** the repository to your GitHub account.
2. **Clone** your forked repository to your local machine:

    ```bash
    git clone https://github.com/your-username/cipherfiles-translations.git
    ```

3. **Navigate** to the project directory:

    ```bash
    cd cipherfiles-translation
    ```

4. **Create a new branch** for your changes:

    ```bash
    git checkout -b i18n
    ```

### Adding a Translation

1. **Choose** the language you want to contribute to and check if there isn't an existing translation for it. If there isn't, proceed to the next step.
2. **Copy** the English language json (en.json) inside `/i18n` and **rename** it according to the language code of your target language (You can find the language codes in the `languages.json` file).
3. **Translate** the content of the files in the newly created folder. Make sure to maintain the same file structure and format.
4. **Add** your changes:

    ```bash
    git add .
    ```

5. **Commit** your changes:

    ```bash
    git commit -m "Add [Language] translation"
    ```

6. **Push** your changes to your GitHub repository:

    ```bash
    git push origin i18n
    ```

7. Create a new **Pull Request** (PR) from your forked repository to the `main` branch of the original repository.

8. Await review and **collaboration** with repository maintainers to get your changes merged.

### Updating an Existing Translation

If you want to update an existing translation, follow the same steps as above, but instead of creating a new folder, make changes directly to the existing translation files.

## Questions or Issues?

If you have any questions or encounter issues while contributing, feel free to open an [issue](https://github.com/resolutesystems/cipherfiles-translations/issues) in the repository.
