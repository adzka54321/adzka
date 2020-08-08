# adzka

jslint.options": {
        "vars": true,
        "plusplus": true,
        "browser": false,
        "devel": true,
        "nomen": true,
        "indent": 4,
        "maxerr": 50,
        "es5": true,
        "predef": [
            "brackets",

            "require",
            "define",
            "$",

            "window",
            "setTimeout",
            "clearTimeout",

            "ArrayBuffer",
            "XMLHttpRequest",
            "Uint32Array",
            "WebSocket"
        ]
    },
    "defaultExtension": "js",
    "language": {
        "javascript": {
            "linting.prefer": ["ESLint", "JSLint"],
            "linting.usePreferredOnly": true
        }
    },
    "path": {
        "src/thirdparty/CodeMirror/**/*.js": {
            "spaceUnits": 2,
            "linting.enabled": false
        },
        "src/thirdparty/globmatch.js": {
            "spaceUnits": 2,
            "linting.enabled": false
        }
