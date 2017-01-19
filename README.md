# wine-and-elixir

## Goal

Create an Elixir project to calculate prices

### Starting info

bananas pound .33
wine each  7.99

given:

``` elixir
  items: [
    %{
      "name": "bananas",
      "quantity": 4.5
    },
    %{
      "name": "wine",
      "quantity": 7.99
    }
  ]
```

return:

``` elixir
  %{
    items: [
      %{
        "name": "bananas",
        "quantity": 4.5,
        "cost": 1.49
      },
      %{
        "name": "wine",
        "quantity": 3,
        "cost": 23.97
      }
    ],
    total: 7.64
  }
```

## Create a web app to do the same

Build Phoenix app

First pass, hard coded names and prices in methods, pattern matching.

Hook up API route

Second pass, use db for prices, pattern match for per pound or each

* Add database for prices
* add items/prices to db


