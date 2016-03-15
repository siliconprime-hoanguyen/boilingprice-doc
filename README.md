# boilingprice-doc
## Category
### Get category
```javascrip
GET /api/v1/categories
```
#### Queries
```javascript
{
  numPerPage: number of categories per page, integer, optional.
  pageNum: 0-based, number of page, integer, optional.
}
```
#### Return
```javascript
[
    {
        "_id": "56e78ca9f2404da5f7bfc8e2",
        "name": 4
    },
    {
        "_id": "56e78ca9f2404da5f7bfc8e3",
        "name": 5
    },
    {
        "_id": "56e78ca9f2404da5f7bfc8e4",
        "name": 6
    },
    {
        "_id": "56e78ca9f2404da5f7bfc8e5",
        "name": 7
    }
]
```
