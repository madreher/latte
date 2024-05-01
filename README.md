# Repository Coverage

[Full report](https://htmlpreview.github.io/?https://github.com/madreher/Godrick/blob/python-coverage-comment-action-data/htmlcov/index.html)

| Name                               |    Stmts |     Miss |   Cover |   Missing |
|----------------------------------- | -------: | -------: | ------: | --------: |
| python/godrick/\_\_init\_\_.py     |        0 |        0 |    100% |           |
| python/godrick/communicator.py     |      344 |       56 |     84% |63, 70, 74, 77, 80, 83, 86, 89, 95, 98, 141, 144, 147, 212, 230, 242, 245, 249, 251, 253, 258, 261, 285, 291, 305, 358, 364, 371, 380, 383, 391-400, 425-427, 433, 436, 439, 453-454, 466-470, 477, 480, 492, 494, 497, 503, 528, 531 |
| python/godrick/computeResources.py |      208 |       26 |     88% |9, 12, 23, 25, 30, 35-39, 117, 161, 171-180, 194, 207, 210, 217, 228 |
| python/godrick/launcher.py         |      229 |       15 |     93% |15, 18, 34, 48, 51, 54, 131, 144, 171, 199, 230, 233, 268, 315, 323 |
| python/godrick/port.py             |       21 |        3 |     86% | 11-12, 21 |
| python/godrick/task.py             |      135 |       11 |     92% |67, 74, 80, 85, 90, 95, 99, 147, 159, 173, 176 |
| python/godrick/workflow.py         |      151 |       22 |     85% |19, 25, 30, 32, 35, 38-40, 52, 84, 90, 95, 116, 134, 141, 143, 145, 147, 149, 169, 176, 178, 180 |
|                          **TOTAL** | **1088** |  **133** | **88%** |           |


## Setup coverage badge

Below are examples of the badges you can use in your main branch `README` file.

### Direct image

[![Coverage badge](https://raw.githubusercontent.com/madreher/Godrick/python-coverage-comment-action-data/badge.svg)](https://htmlpreview.github.io/?https://github.com/madreher/Godrick/blob/python-coverage-comment-action-data/htmlcov/index.html)

This is the one to use if your repository is private or if you don't want to customize anything.

### [Shields.io](https://shields.io) Json Endpoint

[![Coverage badge](https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/madreher/Godrick/python-coverage-comment-action-data/endpoint.json)](https://htmlpreview.github.io/?https://github.com/madreher/Godrick/blob/python-coverage-comment-action-data/htmlcov/index.html)

Using this one will allow you to [customize](https://shields.io/endpoint) the look of your badge.
It won't work with private repositories. It won't be refreshed more than once per five minutes.

### [Shields.io](https://shields.io) Dynamic Badge

[![Coverage badge](https://img.shields.io/badge/dynamic/json?color=brightgreen&label=coverage&query=%24.message&url=https%3A%2F%2Fraw.githubusercontent.com%2Fmadreher%2FGodrick%2Fpython-coverage-comment-action-data%2Fendpoint.json)](https://htmlpreview.github.io/?https://github.com/madreher/Godrick/blob/python-coverage-comment-action-data/htmlcov/index.html)

This one will always be the same color. It won't work for private repos. I'm not even sure why we included it.

## What is that?

This branch is part of the
[python-coverage-comment-action](https://github.com/marketplace/actions/python-coverage-comment)
GitHub Action. All the files in this branch are automatically generated and may be
overwritten at any moment.