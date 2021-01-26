# Welcome to Fetsy Seller

[![Watch the video](https://img.youtube.com/vi/IY8kROYF_1U/maxresdefault.jpg)](https://www.youtube.com/embed/IY8kROYF_1U)

### Get started
- Run `git clone https://github.com/rpt24sourcandy/fetsySeller.git`
- Run `npm install`
- Run `npm run db:setup` and `npm run db:seed` (TODO: combine commands)
- Run `npm start`

### Endpoints
- `/items/:item_id/seller` response will be seller information for given item id
    {
      "item_id": 1
      "seller_id": 1,
      "seller_name": "Forest.Swaniawski14",
      "seller_rating": 3,
      "total_sales": 893,
      "seller_city": "North Gordon",
      "seller_state": "Oklahoma",
      "on_etsy_since": 2019,
    }

