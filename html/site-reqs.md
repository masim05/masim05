# Problem statement

Imagine you are a frontend web developer, create an html page with following requirements:

## Layout

The page should consist of left sidebar, main area and footer in the bottom. The page should be of light colors. Left side bar bar should be places to the left on the main area, they should be aligned vertically. Footer should take the full page width, and be placed below main area.

### Left side bar

Left side bar should contain the following items: arkeo, band. When user clicks an item of the left sidebar the item should be highlighted. There should be indication of the active item in the URL with anchors.

### Main area

If no item at the left side bar selected then the following text should be shown in the main area: Select blockchain on the left.
Once an item at the left side bar is selected , the information should be shown: chain Id, RPC url, API url, gRPC url, peer. The data should be taken from json like:

```json
[
    {
        name: "arkeo",
        chainId: "cid",
        rpc:"xxx",
        api:"yyy",
        gprc:"zzz",
        peer:"link",
    },
    {
        name: "band",
        chainId: "cid",
        rpc:"xxx",
        api:"yyy",
        gprc:"zzz",
        peer:"link",
    },
]
```

It should be possible to copy the value of rpc url, grpc url, api url and peer with one click. The button to copy the value should be placed to the right of the value itself.

### Footer

Footer with the following information: link to https://github.com/masim05, it should be github octocat small image.
