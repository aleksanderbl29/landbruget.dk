---
title: "Side med tabeller"
---

På denne side vil du finde spændende tabeller.

```query1_side
select * from needful_things.orders
```

<DataTable data={query1_side}/>


<DataTable data={query1_side}>
  <Column id=id fmt=num align=left/>
  <Column id=first_name/>
  <Column id=last_name/>
</DataTable>

<BigValue
  data={query1_side}
  value=order_month
/>


