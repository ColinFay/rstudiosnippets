# rstudiosnippets

Just somewhere to share some RStudio Snippets I use. 

## R6 Class

``` 
snippet R6
	${0:name} <- R6::R6Class(
		"${0:name}", 
		public = list(
			initialize = function() {
		
		},
		finalize = function() {
	
		}
		), 
		private = list(
	
		)
	)
```

## Todo 

```
snippet todo
	# TODO ${0:what}
```

