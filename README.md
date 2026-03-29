# Quick facts

```python
import logging
import random


logging.basicConfig(
    level=logging.INFO,
    format="[%(levelname)s]: %(message)s",
)
logger = logging.getLogger()


ACTIVITIES = [
  "write code",
  "design, implement and debug data pipelines",
  "have a lot of meetings",
  "talk in English a lot",
  "turn the stakeholders desires into features",
  "crush a lot of bugs —no wildlife harmed though,",
  "write, read, and eat Python",
]


def main():
    logger.info(f"I {random.choice(ACTIVITIES)} for a living.")


if __name__ == "__main__":
    main()
```

For a life...

* I take photos.
* I build websites.
  * Like a website to showcase my [black & white photography](https://monocromo.blog).
  * Or another one for [photo albums —and maybe stories](https://paliacate.blog).
* I walk. Fast.
* I write.
  * And built a [personal blog](https://quiroptero.blog) of course!
* I build tools. Check out this GitHub!
* I organize photowalks, read a lot and watch movies.

Things I like?

* Bats
* The Cure
* Zdzisław Beksiński
* Talking to people
* Wandering
* Terry Pratchett's books

We can [get in touch](mailto:www@osvaldomiranda.me)!
