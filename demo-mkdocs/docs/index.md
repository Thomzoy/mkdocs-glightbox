# MkDocs GLightbox 

A MkDocs plugin supports image lightbox with [GLightbox](https://github.com/biati-digital/glightbox).

GLightbox is a pure javascript lightbox library with mobile support.

[Hover me](https://example.com "I'm a tooltip!")

## Dependency

1. Python Package
    1. beautifulsoup4>=4.11.1
2. GLightbox javascript file and css file
    1. GLightbox==3.2.0

## Usage

1. Install plugin from pypi

    ```bash
    pip install mkdocs-glightbox
    ```

2. Add ```glightbox``` plugin to your mkdocs.yml plugins sections:

    ```yaml
    plugins:
       - glightbox
    ```

3. You may customize the plugin by passing options in mkdocs.yml:

    ```yaml
    plugins:
       - glightbox:
           touchNavigation: true
           loop: false
           effect: zoom
           width: 100%
           height: auto
           zoomable: true
           draggable: true
    ```

    | Option          | Default | Description                                                                                                  |
    | --------------- | ------- | ------------------------------------------------------------------------------------------------------------ |
    | touchNavigation | true    | Enable or disable the touch navigation (swipe).                                                              |
    | loop            | false   | Loop slides on end.                                                                                          |
    | effect          | zoom    | Name of the effect on lightbox open. (zoom, fade, none)                                                      |
    | width           | 100%    | Default width for inline elements and iframes. You can use any unit for example 90% or 100vw for full width. |
    | height          | auto    | Default height for inline elements and iframes. You can use any unit for example 90%, 100vh or auto.         |
    | zoomable        | true    | Enable or disable zoomable images.                                                                           |
    | draggable       | true    | Enable or disable mouse drag to go prev and next slide.                                                      |

    Check more options information on [GLightbox Docs](https://github.com/biati-digital/glightbox#lightbox-options).

4. For more flexibility, you can disable lightbox by a [specific image](./disable/image.md) or a [specific page](./disable/page.md).

## Demo

Click the image to try lightbox and enjoy the view of Taiwan.

![Sunset over Taipei City](./images/thomas-tucker-sunset-over-taipei-city.jpg) 
Sunset over Taipei City. Credit: [Thomas Tucker](https://unsplash.com/photos/au3CYbd7vCU)

![Lanyu, Taiwan](./images/robson-hatsukami-morgan-lanyu.jpg) 
Lanyu, Taiwan. Credit: [Robson Hatsukami Morgan](https://unsplash.com/photos/T8LZZvKc9Jc)

![Kenting, Taiwan](./images/yuhan-chang-kenting.jpg){ .off-glb }
Kenting, Taiwan. Credit: [Yuhan Chang](https://unsplash.com/photos/ROWXoqmqyjk)

<figure markdown>
  [![Image title](./images/yuhan-chang-kenting.jpg){ .off-glb }](./stats_summary.html)
</figure>

## License

This project is licensed under the MIT License - see the [LICENSE.md](https://github.com/Blueswen/mkdocs-glightbox/blob/main/LICENSE) file for details.
<table>
<thead>
  <tr>
    <th>lalala</th>
    <th>jirejfgre</th>
    <th>jfiozjfroe</th>
    <th>ffjeizozfz</th>
    <th>feiozef</th>
    <th>fjeiof</th>
    <th>fferiofoze</th>
    <th>freofer</th>
    <th>fenofer</th>
    <th>fezofre</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td></td>
    <td>vfd</td>
    <td></td>
    <td></td>
    <td></td>
    <td>ddd</td>
    <td></td>
    <td>d</td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td></td>
    <td>d</td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td></td>
    <td></td>
    <td>d</td>
    <td></td>
    <td></td>
    <td>d</td>
    <td></td>
    <td></td>
    <td>d</td>
    <td></td>
  </tr>
  <tr>
    <td></td>
    <td>d</td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td>d</td>
    <td></td>
    <td>d</td>
    <td></td>
  </tr>
  <tr>
    <td></td>
    <td></td>
    <td></td>
    <td>d</td>
    <td>d</td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
</tbody>
</table>