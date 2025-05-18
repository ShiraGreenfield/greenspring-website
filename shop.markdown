---
layout: page
permalink: /shop/
---

<h2>Our Shop</h2>
<br/>
<div id='product-component-1747583643395' style="margin: 0 auto"></div>
<script type="text/javascript">
/*<![CDATA[*/
(function () {
  var scriptURL = 'https://sdks.shopifycdn.com/buy-button/latest/buy-button-storefront.min.js';
  if (window.ShopifyBuy) {
    if (window.ShopifyBuy.UI) {
      ShopifyBuyInit();
    } else {
      loadScript();
    }
  } else {
    loadScript();
  }
  function loadScript() {
    var script = document.createElement('script');
    script.async = true;
    script.src = scriptURL;
    (document.getElementsByTagName('head')[0] || document.getElementsByTagName('body')[0]).appendChild(script);
    script.onload = ShopifyBuyInit;
  }
  function ShopifyBuyInit() {
    var client = ShopifyBuy.buildClient({
      domain: '1m8ff1-ef.myshopify.com',
      storefrontAccessToken: '238bbe7ec79be10396ac83888f8e6a45',
    });
    ShopifyBuy.UI.onReady(client).then(function (ui) {
      ui.createComponent('product', {
        id: '8118047572105',
        node: document.getElementById('product-component-1747583643395'),
        moneyFormat: '%24%7B%7Bamount%7D%7D',
        options: {
  "product": {
    "styles": {
      "product": {
        "@media (min-width: 601px)": {
          "max-width": "calc(25% - 20px)",
          "margin-left": "20px",
          "margin-bottom": "50px"
        }
      },
      "button": {
        ":hover": {
          "background-color": "#74985f"
        },
        "background-color": "#81a969",
        ":focus": {
          "background-color": "#74985f"
        },
        "border-radius": "5px",
        "padding-left": "25px",
        "padding-right": "25px"
      }
    },
    "text": {
      "button": "Add to cart"
    }
  },
  "productSet": {
    "styles": {
      "products": {
        "@media (min-width: 601px)": {
          "margin-left": "-20px"
        }
      }
    }
  },
  "modalProduct": {
    "contents": {
      "img": false,
      "imgWithCarousel": true,
      "button": false,
      "buttonWithQuantity": true
    },
    "styles": {
      "product": {
        "@media (min-width: 601px)": {
          "max-width": "100%",
          "margin-left": "0px",
          "margin-bottom": "0px"
        }
      },
      "button": {
        ":hover": {
          "background-color": "#74985f"
        },
        "background-color": "#81a969",
        ":focus": {
          "background-color": "#74985f"
        },
        "border-radius": "5px",
        "padding-left": "25px",
        "padding-right": "25px"
      }
    },
    "text": {
      "button": "Add to cart"
    }
  },
  "option": {},
  "cart": {
    "styles": {
      "button": {
        ":hover": {
          "background-color": "#74985f"
        },
        "background-color": "#81a969",
        ":focus": {
          "background-color": "#74985f"
        },
        "border-radius": "5px"
      }
    },
    "text": {
      "total": "Subtotal",
      "button": "Checkout"
    }
  },
  "toggle": {
    "styles": {
      "toggle": {
        "background-color": "#81a969",
        ":hover": {
          "background-color": "#74985f"
        },
        ":focus": {
          "background-color": "#74985f"
        }
      }
    }
  }
},
      });
    });
  }
})();
/*]]>*/
</script>