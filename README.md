# "getBoxObjectFor()" compatibility library for Firefox 3.6-56

This project is obsolete and not maintained anymore.

## Usage

    // use instead of HTMLDocument.getBoxObjectFor(HTMLElement)
    var boxObject = window['piro.sakura.ne.jp']
                      .boxObject
                      .getBoxObjectFor(HTMLElement);

