# Germanisti Keyboard Layout

_Born in the [#Länd][laend], to make the world an ε better!_

Welcome to the **Germanisti** keyboard layout repository! The name "Germanisti"
combines the Greek word "Γερμανία" (germania), meaning "German", with
"επιστήμη" (episteme), meaning "science". This layout is designed specifically
for the programming, mathematical, and scientific community, providing a
comfortable and efficient typing experience in UTF-8 while supporting German
[umlauts (diacritic)][umlaut].

Full layout is depicted in [germanisti.toml](./germanisti.toml).

![img](./dist/germanisti.svg)

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

- **Currency Support** 💶: The Euro symbol (€) is included. (Even a big epsilon 
  can be neglected!)

- **German Umlauts at Default Locations** 🇩🇪: German umlauts and sharp S (ß)
  are placed at their default locations (with AltGr), providing a consistent
  experience for users familiar with full German character support.

- **Commonly Used Mathematical Symbols** ➕: Access frequently used
  mathematical symbols such as ≠ (unequal), ≈ (approx equal), ∝ (propto), ≤
  (less equal), ≥ (greater equal), ∪ (union), ∩ (intersection), ∈ (element of), ∉
  (not element of), ∞ (infinity), ∀ (for all), ∅ (empty set), and ∫ (integral).

- **Number Super and Subscript** ²³: Easily type super and subscript
  numbers for mathematical powers and indices, including the radical symbol
  (√).

- **Caps Lock Mapped to Escape** ⌨️: For an opinionated Vim experience, the Caps
  Lock key is mapped to Escape, allowing for transitions between modes as
  (almost) intended by [Bill Joy][vi] himself.

## Installation

The [instructions for
installation](./installation.rst#using-distributable-layouts) of keyboard
layouts are copied from
[OneDeadKey/kalamine](https://github.com/OneDeadKey/kalamine/tree/main) for
convenience, which are distributed under MIT license.

## Install Kalamine for Layout Developers

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

## License

This project is licensed under the MIT License.

[laend]: https://www.thelaend.de/en/
[umlaut]: https://en.wikipedia.org/wiki/Umlaut_(diacritic)
[vi]: https://en.wikipedia.org/wiki/Vi_(text_editor)#:~:text=Joy%20used%20a%20Lear%20Siegler%20ADM-3A%20terminal
