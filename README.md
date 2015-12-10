# stupidmime

Stupid mime detection for limited PHP environments like Google AppEngine Sandbox.

## What does it do?

This contains a simple helper function ``get_file_mime_type`` which accepts a file location string like
``/foo/bar.jpg`` and it will guess the mime type via the file extension.

It will use the php module ``fileinfo`` if present. If not, it will guess with a simple internal table.

## Installation

```
composer require cedricziel/stupidmime
```
