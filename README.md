# Livewire Turbolinks Plugin

If you are using Turbolinks AND Livewire on the same page, this plugin is required.

## Livewire Version Support
(Livewire version 1.x suports Turbolinks out of the box)

Livewire Version | Turbolinks Plugin Version
--- | ---
2.x | 0.1.x

## Installation
### CDN
Include the CDN asset after `@livewireScripts` or  `<livewire:scripts>` in your app's HTML:

> Note: You MUST have the `data-turbolinks-eval="false"` added to the script tag.

```html
    ...
    @livewireScripts
    <script src="https://cdn.jsdelivr.net/gh/livewire/turbolinks@v0.1.x/dist/livewire-turbolinks.js" data-turbolinks-eval="false"></script>
</body>
```
