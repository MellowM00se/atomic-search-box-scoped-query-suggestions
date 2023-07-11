# Using the Scoped Query Suggestions component

The `atomic-search-box-scoped-query-suggestions` component caters to commerce implementations by providing scoped field suggestions based on the current query suggestions. By leveraging the [Headless FieldSuggestions controller](https://docs.coveo.com/en/headless/latest/reference/search/controllers/field-suggestions/), we are able to achieve suggestions that are similar to what you can find on commerce websites such as Amazon and Best Buy.

The `atomic-search-box-scoped-query-suggestions` component is intended to be used in place of the official `atomic-search-box-query-suggestions` component. To use, simply include the `atomic-search-box-scoped-query-suggestions` component as a child of the `atomic-search-box` component and specify the `field` for which you would like scoped suggestions to be provided.

## Props
- `field`: The field by which suggestions will be provided.
- `icon`: The SVG icon to display.

## Example
```
<atomic-search-box>
    <atomic-search-box-scoped-query-suggestions field="source"></atomic-search-box-scoped-query-suggestions>
</atomic-search-box>
```