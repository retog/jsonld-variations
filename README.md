# jsonld-variations
The same content expressed in different ways

product.json: https://search.google.com/structured-data/testing-tool#url=https%3A%2F%2Fretog.github.io%2Fjsonld-variations%2Fproduct.json

product-expanded.json is also legal Json-LD that expresses exactly the same than product.json, but google thinks that it has 18 errors: https://search.google.com/structured-data/testing-tool/u/0/#url=https%3A%2F%2Fretog.github.io%2Fjsonld-variations%2Fproduct-expanded.json

product-comapcted.json is also the same, google this time thinks it has 7 errors: https://search.google.com/structured-data/testing-tool/u/0/#url=https%3A%2F%2Fretog.github.io%2Fjsonld-variations%2Fproduct-compacted.json


Variants craetes by the JSON-LD Playground: https://json-ld.org/playground/#startTab=tab-compacted&json-ld=%7B%22%40context%22%3A%22http%3A%2F%2Fschema.org%2F%22%2C%22%40type%22%3A%22Product%22%2C%22name%22%3A%22Executive%20Anvil%22%2C%22image%22%3A%5B%22https%3A%2F%2Fexample.com%2Fphotos%2F1x1%2Fphoto.jpg%22%2C%22https%3A%2F%2Fexample.com%2Fphotos%2F4x3%2Fphoto.jpg%22%2C%22https%3A%2F%2Fexample.com%2Fphotos%2F16x9%2Fphoto.jpg%22%5D%2C%22description%22%3A%22Sleeker%20than%20ACME's%20Classic%20Anvil%2C%20the%20Executive%20Anvil%20is%20perfect%20for%20the%20business%20traveler%20looking%20for%20something%20to%20drop%20from%20a%20height.%22%2C%22mpn%22%3A%22925872%22%2C%22brand%22%3A%7B%22%40type%22%3A%22Thing%22%2C%22name%22%3A%22ACME%22%7D%2C%22aggregateRating%22%3A%7B%22%40type%22%3A%22AggregateRating%22%2C%22ratingValue%22%3A%224.4%22%2C%22reviewCount%22%3A%2289%22%7D%2C%22offers%22%3A%7B%22%40type%22%3A%22Offer%22%2C%22priceCurrency%22%3A%22USD%22%2C%22price%22%3A%22119.99%22%2C%22priceValidUntil%22%3A%222020-11-05%22%2C%22itemCondition%22%3A%22http%3A%2F%2Fschema.org%2FUsedCondition%22%2C%22availability%22%3A%22http%3A%2F%2Fschema.org%2FInStock%22%2C%22seller%22%3A%7B%22%40type%22%3A%22Organization%22%2C%22name%22%3A%22Executive%20Objects%22%7D%7D%7D&context=%7B%7D
