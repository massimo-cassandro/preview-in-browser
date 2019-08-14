# Preview in Browser

VS code extension to preview a file in browser, using local web server if defined (otherwise, `file://` protocol is used).

Web Server domain can be set in workspace setting.

Furthermore, a specific browser can be set for previews (default: Firefox Developer Edition).

**Preview in Browser** uses [opn](https://github.com/pwnall/node-open) to launch the browser app.

Browser name is platform dependant as reported in [opn readme](https://github.com/sindresorhus/opn#readme):

> The app name is platform dependent. Don't hard code it in reusable modules. Eg. Chrome is `google chrome` on OS X, `google-chrome` on Linux and `chrome` on Windows.

This extension was inspired by [vscode-extensions-open-in-browser](https://github.com/SudoKillMe/vscode-extensions-open-in-browser) and by [vscode-local-web-opener](https://github.com/Tairraos/vscode-local-web-opener)
