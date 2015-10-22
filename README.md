# blocks
## variables:
$block-padding-y:       2rem !default;
$block-padding-x:       0 !default;

$block-padding-y-xs:    0.5rem !default;
$block-padding-x-xs:    0 !default;

$block-padding-y-sm:    1.5rem !default;
$block-padding-x-sm:    0 !default;

$block-padding-y-lg:    4rem !default;
$block-padding-x-lg:    0 !default;

$block-inverse-color:   #fff !default;
$block-title-size:      3rem !default;
$block-description-size:2rem !default;

$block-image-size:      cover !default;
$block-image-position:  50% 50% !default;
$opacity-md:            0.8 !default;
$opacity-lg:            0.6 !default;
$opacity-sm:            0.4 !default;
$opacity-xs:            0.2 !default;

##classes

classes global:
.block

classes modifiers:
.block-fill-height
.block-collapse
.block-inverse
.block-overlay
.block-relative

classes modifiers (size):
.block-xs 
.block-sm
.block-lg

classes modifiers (overlay):
.block-overlay-opacity-lg
.block-overlay-opacity-sm
.block-overlay-opacity-xs

child classes:
.block-header
.block-content
.block-footer
.block-inner
.block-title
.block-description


Fetch manage:
"blocks": "https://github.com/djvang/blocks/archive/master.zip"
