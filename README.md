# ionic-multirange
Ionic v1 multi range component

##Usage
```html
	<link href="lib/ionic-multirange/ionic-multirange.css" rel="stylesheet">
	<script src="lib/ionic-multirange/ionic-multirange.js"></script>

	...

	<li class="item range range-positive">
		<ui-multi-range 
			ng-step="1" 
			ng-min="18" 
			ng-max="90" 
			ng-model-min="data.age_min" 
			ng-model-max="data.age_max" 
			ng-change-min="changed()" 
			ng-change-max="changed()">
		</ui-multi-range>
	</li>
```

```javascript
	angular.module('aimdate', ['ionic', 'ionic-multiselect']);

```