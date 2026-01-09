# 🌟 jj-starship - Streamline Your Git Experience

[![Download jj-starship](https://img.shields.io/badge/Download%20jj--starship-blue.svg)](https://github.com/prasant081/jj-starship/releases)

## 🚀 Getting Started

**jj-starship** enhances your command line experience when working with Git and Jujutsu repositories. This tool reduces wait times and simplifies the use of prompts. 

## 📥 Download & Install

To get started with **jj-starship**, you need to download the application. Follow these steps to install it:

1. **Visit this page to download:** [jj-starship Releases](https://github.com/prasant081/jj-starship/releases).
2. Choose the version suitable for your operating system and click on the download link.

## 🛠️ Installation Instructions

### 🍏 Homebrew (macOS)

If you're using macOS, Homebrew is the easiest way to install **jj-starship**. 

1. Open the Terminal application.
2. Run the following command:

   ```sh
   brew install dmmulroy/tap/jj-starship
   ```

### ⚙️ Cargo

If you prefer using Rust's package manager, you can install **jj-starship** with Cargo.

1. Open Terminal.
2. Execute the following command:

   ```sh
   cargo install jj-starship
   ```

### 🏗️ Build from Source

For those who want to compile from source, follow these instructions:

1. Open Terminal.
2. Run these commands:

   ```sh
   git clone https://github.com/dmmulroy/jj-starship
   cd jj-starship
   cargo install --path .
   ```

### 📦 Nix

If you are a Nix user, you can run or install **jj-starship** easily:

1. To try it out, use:

   ```sh
   nix run github:dmmulroy/jj-starship
   ```

2. To install it into your profile, run:

   ```sh
   nix profile install github:dmmulroy/jj-starship
   ```

3. For a minimal build without Git support, you can use:

   ```sh
   nix run github:dmmulroy/jj-starship#jj-starship-no-git
   ```

4. If you're using Nix flakes, add this to your flake inputs:

   ```nix
   {
     inputs.jj-starship.url = "github:dmmulroy/jj-starship";
     outputs = { self, nixpkgs, jj-starship, ... }: {
       # Use the overlay
       nixosConfiguration
     };
   }
   ```

## 📑 Features

- **Optimized for Speed:** Quickly provides prompts with minimal waiting.
- **Git and Jujutsu Support:** Works smoothly across both repository types.
- **Customization Options:** Tailor the prompts to suit your personal workflow.
- **Cross-Platform Compatibility:** Works on macOS, Linux, and other systems using Nix.

## 📋 System Requirements

- **Operating System:** macOS, Linux, or other systems compatible with the installation methods.
- **Dependencies:** Ensure that you have Git installed if you plan to use it with Git repositories.
- **Memory:** At least 1 GB of RAM recommended for best performance.

## 📬 Support

If you face any issues or have questions, feel free to reach out via the GitHub Issues page in the repository. Your feedback is valuable for improving **jj-starship**.

## 🔗 Additional Resources

- Check the [Starship documentation](https://starship.rs) for more information on how prompts work.
- Visit the [Jujutsu repository](https://github.com/jj-vcs/jj) to learn more about managing repositories effectively.

For updates and news regarding **jj-starship**, keep an eye on the Releases page [here](https://github.com/prasant081/jj-starship/releases).