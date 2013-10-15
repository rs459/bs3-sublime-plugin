Twitter Bootstrap 3 Jade
==================
Sublime Text Plugin
==================

### Feel free to contribute
- [@rs459 on Twitter](https://twitter.com/rs459)
- [Opening an issue, contributing, proposing enhancement](https://github.com/rs459/bs3-jade-sublime-plugin/issues)

#### TODO
- Improve cursor positioning.
- Automated Testing ?
- Snippet for all class name of BS3 ?

#### This plugin is a fork of [JasonMortonNZ/bs3-sublime-plugin](https://github.com/JasonMortonNZ/bs3-sublime-plugin/) by [@JasonMortonNZ on Twitter](https://twitter.com/jasonmortonnz)

A sublime plugin complete with Twitter Bootstrap 3 snippets


## What's included - contents
- [CDN](#cdn)
- [Templates](#templates)
- [Forms](#forms)
- [Tables](#tables)
- [Input](#input-fields-form-fields)
- [Alerts](#alerts)
- [Badges](#badges)
- [Breadcrumbs](#breadcrumbs)
- [Buttons](#buttons)
- [Grid](#grid)
- [Images](#images)
- [Icons](#icons)
- [Labels](#labels)
- [Pagination](#pagination)
- [Navigation](#navigation)
- [Panels](#panels)
- [List Groups](#list-groups)
- [Media Objects](#media-objects)
- [Icons](#icons)
- [Clearfix](#clearfix)


### CDN

| Component                      | Snippet code                   |
|------------------------------- | :-----------------------------:|
| CDN link (both CSS & JS)       | bst-cdn                        |
| CDN link (CSS only)            | bst-cdn:css                    |
| CDN link (JS only)             | bst-cdn:js                     |

### Templates

| Component                                                                        | Snippet code                   |
|--------------------------------------------------------------------------------- | -----------------------------  |
| HTML5 Template Layout                                                            | bst-template:html5             |
| H5BP layout Template                                                             | bst-h5bp-layout-jade           |
| H5BP index Template                                                              | bst-h5bo-index-jade            |
| [BS3 carousel](http://getbootstrap.com/examples/)                                | bst-tpl-carousel               |
| [BS3 grid](http://getbootstrap.com/examples/grid/)                               | bst-tpl-grid                   |
| [BS3 jumbotron narrow](http://getbootstrap.com/examples/jumbotron-narrow/)       | bst-tpl-jumbotron-narrow       |
| [BS3 jumbotron](http://getbootstrap.com/examples/jumbotron/)                     | bst-tpl-jumbotron              |
| [BS3 justified nav](http://getbootstrap.com/examples/justified-nav)              | bst-tpl-justified-nav          |
| [BS3 navbar fixed top](http://getbootstrap.com/examples/navbar-fixed-top)        | bst-tpl-navbar-fixed-top       |
| [BS3 navbar static top](http://getbootstrap.com/examples/navbar-static-top)      | bst-tpl-navbar-static-top      |     
| [BS3 navbar](http://getbootstrap.com/examples/navbar)                            | bst-tpl-navbar                 |
| [BS3 non responsive](http://getbootstrap.com/examples/non-responsive)            | bst-tpl-non-responsive         |
| [BS3 offcanvas](http://getbootstrap.com/examples/offcanvas/)                     | bst-tpl-offcanvas              |
| [BS3 signin](http://getbootstrap.com/examples/signin/)                           | bst-tpl-starter-signin         |
| [BS3 signin](http://getbootstrap.com/examples/starter-template/)                 | bst-tpl-starter-template       |
| [BS3 sticky footer navbar](http://getbootstrap.com/examples/sticky-footer-navbar)| bst-tpl-sticky-foote-navbar    |
| [BS3 sticky footer](http://getbootstrap.com/examples/sticky-footer)              | bst-tpl-sticky-footer          |
| [BS3 theme](http://getbootstrap.com/examples/theme)                              | bst-tpl-theme                  |

### Forms

| Component       				 | Snippet code        			  |
|------------------------------- | -----------------------------  |
| Form            				 | bst-form            			  |
| Inline Form     				 | bst-form:inline     			  |
| Horizontal Form 				 | bst-form:horizontal 			  |

### Tables

| Component                		 | Snippet code                   |
|------------------------------- | ----------------------------   |
| Table                    		 | bst-table                      |
| Bordered Table           		 | bst-table:bordered             |
| Condensed Table          		 | bst-table:condensed            |
| Hover Table              		 | bst-table:hover                |
| Striped Table            		 | bst-table:striped              |

### Input Fields (Form fields)

**Note:** you can add " :h " to the end of any input field snippet to make it compatible with Twitter Bootstrap 3 horizontal forms. **E.g.**
- bst-input:text:h
- bst-input:hidden:h


| Component                		 | Snippet code                   | Options |
|------------------------------- | ------------------------------ | :-----:	|
| Label		 					 | bst-input:label   			  |    		|
| Text Input               		 | bst-input:text 				  | :h 		|
| Email Input 					 | bst-input:email   			  | :h 		|
| Password Input				 | bst-input:password  			  | :h 		|
| Hidden Input					 | bst-input:hidden  			  | :h 		|
| Url Input						 | bst-input:url 	 			  | :h 		|
| Color Input 					 | bst-input:color   			  | :h 		|
| Number Input 					 | bst-input:number   			  | :h 		|
| Range Input 					 | bst-input:range   			  | :h 		|
| Date Input 					 | bst-input:date   			  | :h 		|
| Week Input 					 | bst-input:week   			  | :h 		|
| Month Input 					 | bst-input:month   			  | :h 		|
| Time Input 					 | bst-input:time   			  | :h 		|
| Tel Input 					 | bst-input:tel   	 			  | :h 		|
| Search Input 					 | bst-input:search   			  | :h 		|
| Reset Input 					 | bst-input:reset   			  | :h 		|
| Submit Input 					 | bst-input:submit   			  | :h 		|
| Checkbox Input 				 | bst-input:checkbox  			  | :h 		|
| Radio Box Input 				 | bst-input:radio  			  | :h 		|

### Alerts

| Component                		 | Snippet code                   |
|------------------------------- | ------------------------------ |
| Alert Box (Default)			 | bst-alert 					  |
| Danger Alert Box				 | bst-alert:danger 			  |
| Info Alert Box				 | bst-alert:info				  |
| Success Alert Box				 | bst-alert:success			  |
| Block Alert Box (Default)		 | bst-alert:block				  |
| Danger Block Alert Box		 | bst-alert:block:danger 		  |
| Info Block Alert Box			 | bst-alert:block:info 		  |
| Success Block Alert Box		 | bst-alert:block:success 		  |

### Badges

| Component                		 | Snippet code                   |
|------------------------------- | ------------------------------ |
| Badge (Default) 				 | bst-badge 					  |

### Breadcrumbs

| Component                		 | Snippet code                   |
|------------------------------- | ------------------------------ |
| Breadcrumbs	 				 | bst-breadcrumbs				  |

### Buttons

**Note:** all button snippets below can have any of the following options append to the end of the snippet *.
- :danger
- :default
- :disabled
- :info
- :primary
- :success
- :warning

**An example:**
- bst-button:success
- bst-lg-button:disabled
- bst-block-button:warning

| Component                		 | Snippet code                   | Options |
|------------------------------- | ------------------------------ | :-----:	|
| Button		 				 | bst-button					  |  *		|
| Block Button	 				 | bst-block-button				  |  *		|
| Mini Button		 			 | bst-xs-button				  |	 *		|
| Small Button		 			 | bst-sm-button				  |	 *		|
| Large Button		 			 | bst-lg-button				  |	 *		|
| Button		 				 | bst-button					  |	 *		|

### Grid

**Note:** The bst-col snippet can be used both on its own or with the addition of a colon followed by the number of columns required: **E.g.**

- bst-col
- bst-col:6
- bst-col:12

| Component                		 | Snippet code                   | Options |
|------------------------------- | ------------------------------ | :-----:	|
| Column		 				 | bst-col						  | :1-12	|

### Icons

| Component                      | Snippet code                   |
|------------------------------- | ------------------------------ |
| Glyphicon		                 | bst-icon:glyphicon             |
| Icon (Font Awesome)		     | bst-icon                       |

### Images

| Component                		 | Snippet code                   |
|------------------------------- | ------------------------------ |
| Thumbnail	 					 | bst-thumbnail 				  |
| Thumbnail with content		 | bst-thumbnail:content		  |

### Labels

| Component                		 | Snippet code                   |
|------------------------------- | ------------------------------ |
| Label		 					 | bst-label 	 				  |
| Danger Label					 | bst-label:danger				  |
| Info Label					 | bst-label:info 				  |
| Success Label					 | bst-label:success			  |
| Warning Label					 | bst-label:warning			  |

### Pagination

| Component                		 | Snippet code                   |
|------------------------------- | ------------------------------ |
| Pager		 					 | bst-pager	 				  |
| Aligned Pager             	 | bst-pager:aligned 			  |
| Pagination					 | bst-pagination				  |
| Pagination:small				 | bst-pagination:small			  |
| Pagination:large				 | bst-pagination:large			  |

### Navigation

| Component                		 | Snippet code                   |
|------------------------------- | ------------------------------ |
| Navbar (basic navbar)			 | bst-navbar	 				  |
| Navbar Brand Element			 | bst-navbar:brand				  |
| Navbar Button					 | bst-navbar:button			  |
| Navbar Form 					 | bst-navbar:form 				  |
| Navbar Link 					 | bst-navbar:link 				  |
| Navbar Text 					 | bst-navbar:text 				  |
| Navbar Fixed-Botton			 | bst-navbar:fixed-bottom		  |
| Navbar Fixed-Top				 | bst-navbar:fixed-top			  |
| Navbar Inverse				 | bst-navbar:inverse			  |
| Navbar Responsive				 | bst-navbar:responsive		  |
| Navbar Static-Top				 | bst-navbar:static-top		  |

### Jumbotron

| Component                		 | Snippet code                   |
|------------------------------- | ------------------------------ |
| Jumbotron (ex Hero Unit)		 | bst-jumbotron 				  |

### Panels

| Component                      | Snippet code                   |
|------------------------------- | ------------------------------ |
| Panel                          | bst-panel                      |
| Panel (contextual)             | bst-panel:{warning,success,info,danger,primary}                  |
| Panel (with heading)           | bst-panel:heading              |
| Panel (with footer)            | bst-panel:footer               |

### List-groups

| Component                      | Snippet code                   |
|------------------------------- | ------------------------------ |
| List group                     | bst-list-group                 |
| List group (with badges)       | bst-list-group:badges          |
| List group (linked list)       | bst-list-group:linked          |
| List group (with content)      | bst-list-group:content         |

### Media Objects

| Component                      | Snippet code                   |
|------------------------------- | ------------------------------ |
| Media Object                   | bst-media-object               |


### License

Twitter Bootstrap 3 Jade - Sublime Text Plugin is open-sourced software licensed under the [MIT license](http://opensource.org/licenses/MIT).
