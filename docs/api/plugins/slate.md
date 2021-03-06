<!-- Generated by documentation.js. Update this documentation by updating the source code. -->

### Table of Contents

-   [Plugin][1]
    -   [name][2]
    -   [schema][3]
    -   [plugins][4]
    -   [serialize][5]
    -   [deserialize][6]
    -   [onKeyDown][7]
        -   [Parameters][8]
    -   [hoverButtons][9]
    -   [toolbarButtons][10]
    -   [renderMark][11]
    -   [renderNode][12]

## Plugin

[packages/plugins/content/slate/src/plugins/Plugin.js:30-95][13]

### name

[packages/plugins/content/slate/src/plugins/Plugin.js:34-34][14]

Type: [string][15]

### schema

[packages/plugins/content/slate/src/plugins/Plugin.js:39-42][16]

Type: {nodes: {}?, marks: {}?}

### plugins

[packages/plugins/content/slate/src/plugins/Plugin.js:47-47][17]

### serialize

[packages/plugins/content/slate/src/plugins/Plugin.js:52-55][18]

Type: function (object: {object: [string][15], type: [string][15], data: any}, children: [Array][19]&lt;any>): any

### deserialize

[packages/plugins/content/slate/src/plugins/Plugin.js:60-60][20]

Type: function (el: [Element][21], next: [Function][22]): any

### onKeyDown

[packages/plugins/content/slate/src/plugins/Plugin.js:70-74][23]

This handler is called when any key is pressed

#### Parameters

-   `e` **[Event][24]** the keydown event
-   `data` **{key: [string][15], isMod: [boolean][25], isShift: [boolean][25]}** utilities for hotkey logic
-   `state` **any** the current editor state

Returns **any?** the new editor state if the plugin handles the hotkey

### hoverButtons

[packages/plugins/content/slate/src/plugins/Plugin.js:79-79][26]

### toolbarButtons

[packages/plugins/content/slate/src/plugins/Plugin.js:84-84][27]

### renderMark

[packages/plugins/content/slate/src/plugins/Plugin.js:89-89][28]

Type: [Function][22]

### renderNode

[packages/plugins/content/slate/src/plugins/Plugin.js:94-94][29]

Type: [Function][22]

[1]: #plugin

[2]: #name

[3]: #schema

[4]: #plugins

[5]: #serialize

[6]: #deserialize

[7]: #onkeydown

[8]: #parameters

[9]: #hoverbuttons

[10]: #toolbarbuttons

[11]: #rendermark

[12]: #rendernode

[13]: https://github.com/PeterKottas/editor/blob/ab5ff50a0efa9bd5c7e0fa5fa7d974e858745804/packages/plugins/content/slate/src/plugins/Plugin.js#L30-L95 "Source code on GitHub"

[14]: https://github.com/PeterKottas/editor/blob/ab5ff50a0efa9bd5c7e0fa5fa7d974e858745804/packages/plugins/content/slate/src/plugins/Plugin.js#L34-L34 "Source code on GitHub"

[15]: https://developer.mozilla.org/docs/Web/JavaScript/Reference/Global_Objects/String

[16]: https://github.com/PeterKottas/editor/blob/ab5ff50a0efa9bd5c7e0fa5fa7d974e858745804/packages/plugins/content/slate/src/plugins/Plugin.js#L39-L42 "Source code on GitHub"

[17]: https://github.com/PeterKottas/editor/blob/ab5ff50a0efa9bd5c7e0fa5fa7d974e858745804/packages/plugins/content/slate/src/plugins/Plugin.js#L47-L47 "Source code on GitHub"

[18]: https://github.com/PeterKottas/editor/blob/ab5ff50a0efa9bd5c7e0fa5fa7d974e858745804/packages/plugins/content/slate/src/plugins/Plugin.js#L52-L55 "Source code on GitHub"

[19]: https://developer.mozilla.org/docs/Web/JavaScript/Reference/Global_Objects/Array

[20]: https://github.com/PeterKottas/editor/blob/ab5ff50a0efa9bd5c7e0fa5fa7d974e858745804/packages/plugins/content/slate/src/plugins/Plugin.js#L60-L60 "Source code on GitHub"

[21]: https://developer.mozilla.org/docs/Web/API/Element

[22]: https://developer.mozilla.org/docs/Web/JavaScript/Reference/Statements/function

[23]: https://github.com/PeterKottas/editor/blob/ab5ff50a0efa9bd5c7e0fa5fa7d974e858745804/packages/plugins/content/slate/src/plugins/Plugin.js#L70-L74 "Source code on GitHub"

[24]: https://developer.mozilla.org/docs/Web/API/Event

[25]: https://developer.mozilla.org/docs/Web/JavaScript/Reference/Global_Objects/Boolean

[26]: https://github.com/PeterKottas/editor/blob/ab5ff50a0efa9bd5c7e0fa5fa7d974e858745804/packages/plugins/content/slate/src/plugins/Plugin.js#L79-L79 "Source code on GitHub"

[27]: https://github.com/PeterKottas/editor/blob/ab5ff50a0efa9bd5c7e0fa5fa7d974e858745804/packages/plugins/content/slate/src/plugins/Plugin.js#L84-L84 "Source code on GitHub"

[28]: https://github.com/PeterKottas/editor/blob/ab5ff50a0efa9bd5c7e0fa5fa7d974e858745804/packages/plugins/content/slate/src/plugins/Plugin.js#L89-L89 "Source code on GitHub"

[29]: https://github.com/PeterKottas/editor/blob/ab5ff50a0efa9bd5c7e0fa5fa7d974e858745804/packages/plugins/content/slate/src/plugins/Plugin.js#L94-L94 "Source code on GitHub"
