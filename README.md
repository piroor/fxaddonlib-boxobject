# "getBoxObjectFor()" compatibility library for Firefox 3.6 or later

## Usage

    // use instead of HTMLDocument.getBoxObjectFor(HTMLElement)
    var boxObject = window['piro.sakura.ne.jp']
                      .boxObject
                      .getBoxObjectFor(HTMLElement);

