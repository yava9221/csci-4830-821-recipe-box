# CSCI 4830-821 Recipe Box 

## The Project

This repo is a collection of favorite recipes created by its authors.

## Recipes

The recipes are Markdown formatted files in the `recipes/` directory. The
format is:

```
# Title

## Ingredients

*  <Ingredient 1>
*  <Ingredient 2>
...
*  <Ingredient N>

## Preparation

<Instructions on how to prepare the recipe.>

## <Other sections as required>

## License

<The required license section>
```

## Contributing

Open a [pull request](https://help.github.com/articles/using-pull-requests/) on
GitHub. This project uses the [GitHub
workflow](https://guides.github.com/introduction/flow/).

## Recipe style

A few style guidelines:

1.  Use the pound sign `#` for headers instead of dashes or equals signs. Use
    the leading pound sign only. For example,

    ```
    # Good

    # Bad #

    Bad
    ===
    ```
2.  Wrap all lines to 80 columns max.
3.  When writing lists, take care when wrapping long lines. The text on the
    subsequent lines should line up with the text on the previous line. For
    example, consider this ordered list:

    ```
    # Bad

    1.  A very long step in the ingredient list in which the verbosity causes
    the line to wrap.
    2.  The next step, which we still want to be readable.

    # Good

    1.  A very long step in the ingredient list in which the verbosity causes
        the line to wrap.
    2.  The next step, which we still want to be readable.
    ```
4.  In both ordered and unordered lists where we expect lots of text to wrap,
    the text should be indented 4 spaces. We do this because it allows list
    items with multiple paragraphs. This means that there should be 2 spaces
    after the period in an ordered list and 3 spaces after a star in an
    unordered list. For example:

    ```
    # Good

    1.  Mix
    2.  Bake

    *   Delicious
    *   Nutritious
    ```

## License

CSCI 4830-821 Recipe Box (c) by The CSCI 4830-821 Authors

CSCI 4830-821 Recipe Box is licensed under a [Creative Commons Attribution 4.0
International License](http://creativecommons.org/licenses/by/4.0/).

You should have received a copy of the license along with this
work.  If not, see <http://creativecommons.org/licenses/by/4.0/>.
