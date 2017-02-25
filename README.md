# mantisbt-2.1.x-sample-plugin
My 5 cents trying to help people that need to migrate pluging from 1.2.x to 2.1.x

# function differences
1.2.x html_page_top() => 2.1.x layout_page_header() + layout_page_begin()
1.2.x html_page_bottom1() => 2.1.x layout_page_end()

# localization
use plugin_lang_get() instead of lang_get()

# layout
several standard div are used, examples:

<div class="col-md-12 col-xs-12">
<div class="space-10">
<div class="form-container">
<div class="widget-box widget-color-blue2">
<div class="widget-header widget-header-small">
<div class="widget-toolbox padding-8 clearfix">

