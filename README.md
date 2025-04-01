# Formeo (Fork)

> ⚠️ This is a **fork** of the original [Formeo](https://github.com/Draggable/formeo) project, maintained by **Jonas Habel**.
> 
> This fork includes fixes and enhancements not available in the original version.  
> Please do not confuse this with the official release by Draggable.



## Features

- Drag & drop editing
- Extensible builder with plethora of options
- Column/inline fields
- Custom fields
- Preview mode
- i18n support
- 🧼 **Fork improvements by Jonas Habel:**
- Automatic cleanup of unused form elements (rows, columns, fields)
- Bug fixes and usability tweaks

## Installation


## Usage

To start building forms with this module include formeo.min.js and formeo.min.css in your project and call:

```javascript
import { FormeoEditor, FormeoRenderer } from 'formeo'

// Set up a form builder
const editor = new FormeoEditor(options)

// When you're ready, grab the form data object
// Typically you'd do this in the "onSave" event, which you can configure through the editor's options object
const formData = editor.formData

// Then, when you're ready to render the form, use
const renderer = new FormeoRenderer(options)
renderer.render(formData)
```

## [Docs](https://github.com/Draggable/formeo/blob/master/docs/README.md)

## [Changelog](https://github.com/Draggable/formeo/blob/master/CHANGELOG.md)

## [🙌 Credits]
Original project by Draggable

Fork maintained by Jonas Habel from Flexxter GmbH — improvements and maintenance for extended use cases
