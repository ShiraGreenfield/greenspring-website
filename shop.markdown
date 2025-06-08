---
layout: page
title: Our Shop
permalink: /shop/
---

<div id='product-component-1749387213450' style="margin: 0 auto"></div>
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
        node: document.getElementById('product-component-1749387213450'),
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
      "title": {
        "font-size": "20px"
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
      },
      "price": {
        "font-size": "16px"
      },
      "compareAt": {
        "font-size": "13.6px"
      },
      "unitPrice": {
        "font-size": "13.6px"
      }
    },
    "buttonDestination": "modal",
    "contents": {
      "options": false
    },
    "width": "380px",
    "text": {
      "button": "View product"
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
      },
      "title": {
        "font-family": "Helvetica Neue, sans-serif",
        "font-weight": "bold",
        "font-size": "26px",
        "color": "#4c4c4c"
      },
      "price": {
        "font-family": "Helvetica Neue, sans-serif",
        "font-weight": "normal",
        "font-size": "18px",
        "color": "#4c4c4c"
      },
      "compareAt": {
        "font-family": "Helvetica Neue, sans-serif",
        "font-weight": "normal",
        "font-size": "15.299999999999999px",
        "color": "#4c4c4c"
      },
      "unitPrice": {
        "font-family": "Helvetica Neue, sans-serif",
        "font-weight": "normal",
        "font-size": "15.299999999999999px",
        "color": "#4c4c4c"
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
    },
    "popup": false
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
