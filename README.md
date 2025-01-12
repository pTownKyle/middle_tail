# Middleman Project with Tailwind CSS & AlpineJS Starter Template

This template is for Middleman-based websites featuring **Tailwind CSS** and **AlpineJS** for a lightweight and responsive frontend.

### Changes Made:
- **Gemfile Updates:**
    - Added `dotenv`, `logger`, `benchmark`, `ostruct`, `csv`, and `rdoc` to resolve warnings in Ruby 3.4.1.
    - Compatible with Ruby **3.4.1** and Middleman **4.5.1**.

- **Tailwind CSS** is integrated using `npx tailwindcss` for styling.
- **AlpineJS** is added via CDN to enable dynamic frontend features.

### Ruby Version:
- Works with **Ruby 3.4.1**, with no errors observed for this version.

---


## Installation

 * Run `npm install`
 * Run `bundle install`
 * Run `middleman serve` or `middleman build`


## Usage

This installation uses Tailwind CLI via a [Middleman external pipeline](https://middlemanapp.com/advanced/external-pipeline/) ([source](https://github.com/donnfelker/middlemanapp-tailwindcss-template/blob/main/config.rb#L8)).

When running `middleman serve` Tailwind CLI will watch for any changes to the content files and will then rebuild the CSS as necessary.
When running `middleman build` the app will be built to the `build/` directory.
