e-shop
======

******************
**计划**
*待定*
>计划计划计划计划计划计划计划计划计划计划计划计划计划
 

```javascript
  		bindEvent : function() {
			var _this = this;
			
			$("#aCheckOrder").click(function() {
				_this.checkOrder(this);
			});
			
			$("#J_chg_payWay").click(function(e) {
				e.preventDefault();
				_this.showPayway(true);
				_this.stopSync();
			});
			
		}
```
****
##table
| a | b | c|
|:---:|---|---|
|1 |2  | 3|
