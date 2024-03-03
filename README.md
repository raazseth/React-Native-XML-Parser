# React Native XML Form Renderer

This React Native application allows users to render forms based on XML input. It offers functionalities to display a form from a predefined XML file and to present a form based on user-provided XML input.

## Objective

The main objective of this project is to develop a mobile application using React Native that enables users to render forms dynamically based on XML data.

## Features

- Render forms from a predefined XML file.
- Render forms based on user-provided XML input.
- Support for various field types including text fields, date/time fields, radio buttons, and drawing fields.
- Error handling for invalid XML format or missing elements.
- Cross-platform compatibility with React Native.

## Installation

1. Clone this repository to your local machine.
2. Navigate to the project directory.
3. Run `npm install` to install dependencies.
4. Run the application on your preferred emulator or device using `npx react-native run-android` or `npx react-native run-ios`.

## Usage

- Tap on the "Render Form from XML File" button to display a form from a predefined XML file.
- Tap on the "Render Form from XML Input" button to present a form based on user-provided XML input.

## XML Form Data

The XML data should adhere to the following structure:

```xml
<form>
  <field>
    <type>text</type>
    <label>Name</label>
  </field>
  <field>
    <type>datetime</type>
    <label>Date of Birth</label>
  </field>
  <field>
    <type>radio</type>
    <label>Gender</label>
    <options>
      <option>Male</option>
      <option>Female</option>
      <option>Other</option>
    </options>
  </field>
  <field>
    <type>drawing</type>
    <label>Signature</label>
  </field>
</form>
```
