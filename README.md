# Germanisti Keyboard Layout

Welcome to the **Germanisti** keyboard layout repository! The name "Germanisti"
combines the Greek word "Γερμανία" (germania), meaning "German", with
"επιστήμη" (episteme), meaning "science". This layout is designed specifically
for the programming, mathematical, and scientific community, providing a
comfortable and efficient typing experience while supporting German umlauts
(diacritic) [^1].

Born in the #Länd, to make the world an ε better!

## Features

- **Standard US Layout** 🖥️: The base layer is a standard US layout, ensuring a
  comfortable coding experience. Unlike the traditional German keyboard layout,
  which can make frequently used symbols like parentheses harder to reach,
  Germanisti keeps them easily accessible.

- **No Dead Keys** 🚫: Enjoy a straightforward typing experience—press a key
  and see the output immediately, without any dead keys.

- **AltGr Layer for Greek Alphabet** 🔤: Easily write mathematical formulas and
  scientific notes with the AltGr layer, which provides access to the Greek
  alphabet. This is especially useful when LaTeX or other typesetting tools are
  not available.

- **German Umlauts at Default Locations** 🇩🇪: German umlauts are placed at
  their default locations, providing a consistent experience for users familiar
  with German layouts.

- **Caps Lock Mapped to Escape** ⌨️: For an opinionated Vim experience, the Caps
  Lock key is mapped to Escape, allowing for transitions between modes as
  (almost) intended by Bill Joy himself.

## Installation

To use Germanisti keyboard layout install the layout as is required by your
system.

### Fedora

### Windows

### MacOS

## Installation Instructions (Editing and Testing)

To edit and test the Germanisti keyboard layout, you'll need to install
**Kalamine**. Follow these steps

1. **Install Kalamine**:
    Install from the [Kalamine GitHub
    Repository](https://github.com/OneDeadKey/kalamine/tree/main) and follow
    the installation instructions.

2. **Clone the Repository**:
    ```bash git clone
    https://github.com/yourusername/germanisti-keyboard-layout.git cd
    germanisti-keyboard-layout
    ```

3. **Edit the Layout**: (Optional)
    Open Kalamine and load the layout files from the cloned repository.

4. **Test the Keyboard Layout**:
    Use the following command to watch for changes and test the layout:
    ```bash
    kalamine watch germanisti.toml
    ```
