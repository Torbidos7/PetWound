<p align="center">
  <a href="google.com">
    <img src="https://cdn-icons-png.flaticon.com/512/9316/9316069.png" alt="Automated wound image segmentation: transfer learning from human to pet via active semi-supervised learning" width=72 height=72>
  </a>

  <h3 align="center">Automated wound image segmentation: transfer learning from human to pet via active semi-supervised learning</h3>

  <p align="left">
   An automated pipeline capable of segmenting wound images of animals. 
Active Semi-Supervised Learning techniques were applied for human-wound images to perform segmentation,
then the same models were trained, via Transfer Learning, adopting an Active Semi-Supervised Learning to unlabelled animal-wound images. 
    <br>
    <a href="https://github.com/Torbidos7/PetWound/issues/new?template=bug.md">Report bug</a>
    ·
    <a href="https://github.com/Torbidos7/PetWound/issues/new?template=feature.md&labels=feature">Request feature</a>
  </p>
</p>


## Table of contents

- [Quick start](#quick-start)
- [What's included](#whats-included)
- [Bugs and feature requests](#bugs-and-feature-requests)
- [Contributing](#contributing)
- [Creators](#creators)
- [Thanks](#thanks)
- [Copyright and license](#copyright-and-license)


## Quick start

The frameworks used in this project are

- <a href="https://github.com/qubvel/segmentation_models">segmentation models</a>
- TensorFlow 2.8.0

## What's included

All the available files are structured as follows:

- *read_models.ipynb* is a notebook for fast model loading;
- *models* contains the 4 model produced in the study

```text
Automated-wound-image-segmentation/
├──read_models.ipynb
└──models/
    ├──efficientnet_deepskin_human.h5
    ├──efficientnet_petwound_animal.h5
    ├──mobilenet_deepskin_human.h5
    └──mobilenet_petwound_animal.h5 
     
```

## Bugs and feature requests

Have a bug or a feature request? Please first read the [issue guidelines](https://github.com/Torbidos7/PetWound/blob/master/CONTRIBUTING.md) and search for existing and closed issues. If your problem or idea is not addressed yet, [please open a new issue](https://github.com/Torbidos7/PetWound/issues/new).

## Contributing

Please read through our [contributing guidelines](https://github.com/Torbidos7/PetWound/blob/master/CONTRIBUTING.md). Included are directions for opening issues, coding standards, and notes on development.

Moreover, all HTML and CSS should conform to the [Code Guide](https://github.com/mdo/code-guide), maintained by [Main author](https://github.com/Torbidos7).

Editor preferences are available in the [editor config](https://github.com/Torbidos7/PetWound/blob/master/.editorconfig) for easy use in common text editors. Read more and download plugins at <https://editorconfig.org/>.

## Creators

**Creator 1**

- <https://github.com/Torbidos7/>

## Thanks

Thank you for coming :stuck_out_tongue_closed_eyes:

## Copyright and license

Code and documentation copyright 2011-2018 the authors. Code released under the [MIT License](https://github.com/Torbidos7/PetWound//blob/master/LICENSE).


