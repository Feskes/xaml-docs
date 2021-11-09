---
title: Office2019 Theme
page_title: Office2019 Theme
description: Familiarize yourself with the Office2019 theme, inspired by the well-known Microsoft Office productivity suite and its latest version.
slug: common-styling-appearance-Office2019-theme
tags: Office2019,theme,glyphs,fontsize,fontfamily
published: True
position: 12
---

<style>
.theme-palette-color {
	width:20px;
	height:20px;
	margin: auto;
	border: 1px solid black;
}

.Office2019theme-accentbackgroundbrush{
	background: #106EBE;
}
.Office2019theme-accentborderbrush{
	background: #106EBE;
}
.Office2019theme-accentmouseoverbackgroundbrush{
	background: #D4E8F8;
}
.Office2019theme-accentmouseoverborderbrush{
	background: #2F96ED;
}
.Office2019theme-accentpressedbackgroundbrush{
	background: #A1CDED;
}
.Office2019theme-alternativebackgroundbrush{
	background: #F1F1F1;
}
.Office2019theme-basebackgroundbrush{
	background: #DFDFDF;
}
.Office2019theme-buttonbackgroundbrush{
	background: #E5E5E5;
}
.Office2019theme-checkedforegroundbrush{
	background: #FFFFFF;
}
.Office2019theme-disabledbackgroundbrush{
	background: #F1F1F1;
}
.Office2019theme-disabledborderbrush{
	background: #D6D6D6;
}
.Office2019theme-headerbackgroundbrush{
	background: #106EBE;
}
.Office2019theme-headerforegroundbrush{
	background: #FFFFFF;
}
.Office2019theme-highlightedforegroundbrush{
	background: #2F2F2F;
}
.Office2019theme-iconbrush{
	background: #606060;
}
.Office2019theme-mainbackgroundbrush{
	background: #FFFFFF;
}
.Office2019theme-mainborderbrush{
	background: #ACACAC;
}
.Office2019theme-mainforegroundbrush{
	background: #000000;
}
.Office2019theme-mouseoverbackgroundbrush{
	background: #C8C7C4;
}
.Office2019theme-pressedbackgroundbrush{
	background: #B3AFAD;
}
.Office2019theme-readonlybackgroundbrush{
	background: #FFFFFF;
}
.Office2019theme-readonlyborderbrush{
	background: #ACACAC;
}
.Office2019theme-secondarybackgroundbrush{
	background: #D6D5D5;
}
.Office2019theme-secondaryforegroundbrush{
	background: #000000;
}
.Office2019theme-validationbrush{
	background: #E43E00;
}
/* New brushes since R3 2021 */
.Office2019theme-disabledcheckedforegroundbrush{
	background: #FFFFFF;
}
.Office2019theme-disabledforegroundbrush{
	background: #000000;
}
.Office2019theme-disablediconbrush{
	background: #606060;
}
.Office2019theme-iconwrapperbrush{
	background: transparent;
}
.Office2019theme-selectedunfocusedbackgroundbrush{
	background: #E5E5E5;
}
.Office2019theme-tertiarybackgroundbrush{
	background: #F1F1F1;
}

/* Gray variation */
.Office2019theme-accentbackgroundbrush-gray{
	background: #106EBE;
}
.Office2019theme-accentborderbrush-gray{
	background: #106EBE;
}
.Office2019theme-accentmouseoverbackgroundbrush-gray{
	background: #D4E8F8;
}
.Office2019theme-accentmouseoverborderbrush-gray{
	background: #2F96ED;
}
.Office2019theme-accentpressedbackgroundbrush-gray{
	background: #A1CDED;
}
.Office2019theme-alternativebackgroundbrush-gray{
	background: #CBCBCB;
}
.Office2019theme-basebackgroundbrush-gray{
	background: #767272;
}
.Office2019theme-buttonbackgroundbrush-gray{
	background: #BFBFBF;
}
.Office2019theme-checkedforegroundbrush-gray{
	background: #FFFFFF;
}
.Office2019theme-disabledbackgroundbrush-gray{
	background: #CBCBCB;
}
.Office2019theme-disabledborderbrush-gray{
	background: #BEBEBE;
}
.Office2019theme-headerbackgroundbrush-gray{
	background: #106EBE;
}
.Office2019theme-headerforegroundbrush-gray{
	background: #FFFFFF;
}
.Office2019theme-highlightedforegroundbrush-gray{
	background: #2F2F2F;
}
.Office2019theme-iconbrush-gray{
	background: #333333;
}
.Office2019theme-mainbackgroundbrush-gray{
	background: #E2E2E2;
}
.Office2019theme-mainborderbrush-gray{
	background: #A6A6A6;
}
.Office2019theme-mainforegroundbrush-gray{
	background: #000000;
}
.Office2019theme-mouseoverbackgroundbrush-gray{
	background: #ACACAC;
}
.Office2019theme-pressedbackgroundbrush-gray{
	background: #918E8D;
}
.Office2019theme-readonlybackgroundbrush-gray{
	background: #E2E2E2;
}
.Office2019theme-readonlyborderbrush-gray{
	background: #A6A6A6;
}
.Office2019theme-secondarybackgroundbrush-gray{
	background: #B6B3B1;
}
.Office2019theme-secondaryforegroundbrush-gray{
	background: #FFFFFF;
}
.Office2019theme-validationbrush-gray{
	background: #E43E00;
}
/* New brushes since R3 2021 */
.Office2019theme-disabledcheckedforegroundbrush-gray{
	background: #FFFFFF;
}
.Office2019theme-disabledforegroundbrush-gray{
	background: #000000;
}
.Office2019theme-disablediconbrush-gray{
	background: #333333;
}
.Office2019theme-iconwrapperbrush-gray{
	background: transparent;
}
.Office2019theme-selectedunfocusedbackgroundbrush-gray{
	background: #BFBFBF;
}
.Office2019theme-tertiarybackgroundbrush-gray{
	background: #CBCBCB;
}

/* Dark variation */
.Office2019theme-accentbackgroundbrush-dark{
	background: #106EBE;
}
.Office2019theme-accentborderbrush-dark{
	background: #106EBE;
}
.Office2019theme-accentmouseoverbackgroundbrush-dark{
	background: #D4E8F8;
}
.Office2019theme-accentmouseoverborderbrush-dark{
	background: #2F96ED;
}
.Office2019theme-accentpressedbackgroundbrush-dark{
	background: #A1CDED;
}
.Office2019theme-alternativebackgroundbrush-dark{
	background: #3C3C3C;
}
.Office2019theme-basebackgroundbrush-dark{
	background: #151515;
}
.Office2019theme-buttonbackgroundbrush-dark{
	background: #3D3D3D;
}
.Office2019theme-checkedforegroundbrush-dark{
	background: #FFFFFF;
}
.Office2019theme-disabledbackgroundbrush-dark{
	background: #3F3E3C;
}
.Office2019theme-disabledborderbrush-dark{
	background: #4F4F4F;
}
.Office2019theme-headerbackgroundbrush-dark{
	background: #106EBE;
}
.Office2019theme-headerforegroundbrush-dark{
	background: #FFFFFF;
}
.Office2019theme-highlightedforegroundbrush-dark{
	background: #2F2F2F;
}
.Office2019theme-iconbrush-dark{
	background: #A6A6A6;
}
.Office2019theme-mainbackgroundbrush-dark{
	background: #2F2F2F;
}
.Office2019theme-mainborderbrush-dark{
	background: #606060;
}
.Office2019theme-mainforegroundbrush-dark{
	background: #F1F1F1;
}
.Office2019theme-mouseoverbackgroundbrush-dark{
	background: #B3AFAD;
}
.Office2019theme-pressedbackgroundbrush-dark{
	background: #767676;
}
.Office2019theme-readonlybackgroundbrush-dark{
	background: #2F2F2F;
}
.Office2019theme-readonlyborderbrush-dark{
	background: #606060;
}
.Office2019theme-secondarybackgroundbrush-dark{
	background: #2B2B2B;
}
.Office2019theme-secondaryforegroundbrush-dark{
	background: #F1F1F1;
}
.Office2019theme-validationbrush-dark{
	background: #E43E00;
}
/* New brushes since R3 2021 */
.Office2019theme-disabledcheckedforegroundbrush-dark{
	background: #FFFFFF;
}
.Office2019theme-disabledforegroundbrush-dark{
	background: #F1F1F1;
}
.Office2019theme-disablediconbrush-dark{
	background: #A6A6A6;
}
.Office2019theme-iconwrapperbrush-dark{
	background: transparent;
}
.Office2019theme-selectedunfocusedbackgroundbrush-dark{
	background: #3D3D3D;
}
.Office2019theme-tertiarybackgroundbrush-dark{
	background: #3C3C3C;
}

/* HighContrast variation */
.Office2019theme-accentbackgroundbrush-highcontrast{
	background: #1AEBFF;
}
.Office2019theme-accentborderbrush-highcontrast{
	background: #1AEBFF;
}
.Office2019theme-accentmouseoverbackgroundbrush-highcontrast{
	background: #FFFF00;
}
.Office2019theme-accentmouseoverborderbrush-highcontrast{
	background: #1AEBFF;
}
.Office2019theme-accentpressedbackgroundbrush-highcontrast{
	background: #1AEBFF;
}
.Office2019theme-alternativebackgroundbrush-highcontrast{
	background: #000000;
}
.Office2019theme-basebackgroundbrush-highcontrast{
	background: #000000;
}
.Office2019theme-buttonbackgroundbrush-highcontrast{
	background: #000000;
}
.Office2019theme-checkedforegroundbrush-highcontrast{
	background: #000000;
}
.Office2019theme-disabledbackgroundbrush-highcontrast{
	background: #808080;
}
.Office2019theme-disabledborderbrush-highcontrast{
	background: #FFFFFF;
}
.Office2019theme-headerbackgroundbrush-highcontrast{
	background: #37006E;
}
.Office2019theme-headerforegroundbrush-highcontrast{
	background: #FFFFFF;
}
.Office2019theme-highlightedforegroundbrush-highcontrast{
	background: #000000;
}
.Office2019theme-iconbrush-highcontrast{
	background: #FFFFFF;
}
.Office2019theme-mainbackgroundbrush-highcontrast{
	background: #000000;
}
.Office2019theme-mainborderbrush-highcontrast{
	background: #FFFFFF;
}
.Office2019theme-mainforegroundbrush-highcontrast{
	background: #FFFFFF;
}
.Office2019theme-mouseoverbackgroundbrush-highcontrast{
	background: #1AEBFF;
}
.Office2019theme-pressedbackgroundbrush-highcontrast{
	background: #1AEBFF;
}
.Office2019theme-readonlybackgroundbrush-highcontrast{
	background: #008000;
}
.Office2019theme-readonlyborderbrush-highcontrast{
	background: #FFFFFF;
}
.Office2019theme-secondarybackgroundbrush-highcontrast{
	background: #37006E;
}
.Office2019theme-secondaryforegroundbrush-highcontrast{
	background: #FFFFFF;
}
.Office2019theme-validationbrush-highcontrast{
	background: #EB0300;
}
/* New brushes since R3 2021 */
.Office2019theme-disabledcheckedforegroundbrush-highcontrast{
	background: #808080;
}
.Office2019theme-disabledforegroundbrush-highcontrast{
	background: #00FF00;
}
.Office2019theme-disablediconbrush-highcontrast{
	background: #00FF00;
}
.Office2019theme-iconwrapperbrush-highcontrast{
	background: #000000;
}
.Office2019theme-selectedunfocusedbackgroundbrush-highcontrast{
	background: #808080;
}
.Office2019theme-tertiarybackgroundbrush-highcontrast{
	background: #37006E;
}

article table
{
    table-layout: auto;
}
</style>

# Office2019 Theme

With the **R3 2020** release of the **UI for WPF** suite we have introduced the brand new **Office2019 theme**. Inspired by the well-known Microsoft Office productivity suite and its latest version, the Office2019 theme is here to help re-creating and delivering that fresh and smooth look and feel to your WPF apps. Explore the Light, Gray and Dark built-in color variations of the Office2019 theme and get off to a flying start with your WPF applications.

> With the **R3 2021** release, we have expanded the built-in color variations with a brand-new one - the **HighContrast**. In addition to it, we extended the theme palette with several brushes. Read more in the [Default Theme Colors](#default-theme-colors) topic.

Jump to the following topics to learn about the specifics of the theme's palette and features.

* [Default Theme Colors](#default-theme-colors)
* [Office2019Palette Properties](#office2019palette-properties)
* [Theme Variation Changing](#theme-variation-changing)
* [Font Family and Font Size](#font-family-and-font-size)
* [Glyphs](#glyphs)
* [Theme Helper](#theme-helper)

## Default Theme Colors

The **Office2019 Theme** is designed to be easily modified via the exposed colors in the theme palette.
The default values of the brushes in the theme are listed below.

|Brush name|   |Light|   |Gray|   |Dark|   |HighContrast|
|----------|---|-----|---|----|---|----|---|----|
|**AccentBackgroundBrush**|#106EBE|<div class="theme-palette-color Office2019theme-accentbackgroundbrush"></div>|#106EBE|<div class="theme-palette-color Office2019theme-accentbackgroundbrush-gray"></div>|#106EBE|<div class="theme-palette-color Office2019theme-accentbackgroundbrush-dark"></div>|#1AEBFF|<div class="theme-palette-color Office2019theme-accentbackgroundbrush-highcontrast"></div>|
|**AccentBorderBrush**|#106EBE|<div class="theme-palette-color Office2019theme-accentborderbrush"></div>|#106EBE|<div class="theme-palette-color Office2019theme-accentborderbrush-gray"></div>|#106EBE|<div class="theme-palette-color Office2019theme-accentborderbrush-dark"></div>|#1AEBFF|<div class="theme-palette-color Office2019theme-accentborderbrush-highcontrast"></div>|
|**AccentMouseOverBackgroundBrush**|#D4E8F8|<div class="theme-palette-color Office2019theme-accentmouseoverbackgroundbrush"></div>|#D4E8F8|<div class="theme-palette-color Office2019theme-accentmouseoverbackgroundbrush-gray"></div>|#D4E8F8|<div class="theme-palette-color Office2019theme-accentmouseoverbackgroundbrush-dark"></div>|#FFFF00|<div class="theme-palette-color Office2019theme-accentmouseoverbackgroundbrush-highcontrast"></div>|
|**AccentMouseOverBorderBrush**|#2F96ED|<div class="theme-palette-color Office2019theme-accentmouseoverborderbrush"></div>|#2F96ED|<div class="theme-palette-color Office2019theme-accentmouseoverborderbrush-gray"></div>|#2F96ED|<div class="theme-palette-color Office2019theme-accentmouseoverborderbrush-dark"></div>|#1AEBFF|<div class="theme-palette-color Office2019theme-accentmouseoverborderbrush-highcontrast"></div>|
|**AccentPressedBackgroundBrush**|#A1CDED|<div class="theme-palette-color Office2019theme-accentpressedbackgroundbrush"></div>|#A1CDED|<div class="theme-palette-color Office2019theme-accentpressedbackgroundbrush-gray"></div>|#A1CDED|<div class="theme-palette-color Office2019theme-accentpressedbackgroundbrush-dark"></div>|#1AEBFF|<div class="theme-palette-color Office2019theme-accentpressedbackgroundbrush-highcontrast"></div>|
|**AlternativeBackgroundBrush**|#F1F1F1|<div class="theme-palette-color Office2019theme-alternativebackgroundbrush"></div>|#CBCBCB|<div class="theme-palette-color Office2019theme-alternativebackgroundbrush-gray"></div>|#3C3C3C|<div class="theme-palette-color Office2019theme-alternativebackgroundbrush-dark"></div>|#000000|<div class="theme-palette-color Office2019theme-alternativebackgroundbrush-highcontrast"></div>|
|**BaseBackgroundBrush**|#DFDFDF|<div class="theme-palette-color Office2019theme-basebackgroundbrush"></div>|#767272|<div class="theme-palette-color Office2019theme-basebackgroundbrush-gray"></div>|#151515|<div class="theme-palette-color Office2019theme-basebackgroundbrush-dark"></div>|#000000|<div class="theme-palette-color Office2019theme-basebackgroundbrush-highcontrast"></div>|
|**ButtonBackgroundBrush**|#E5E5E5|<div class="theme-palette-color Office2019theme-buttonbackgroundbrush"></div>|#BFBFBF|<div class="theme-palette-color Office2019theme-buttonbackgroundbrush-gray"></div>|#3D3D3D|<div class="theme-palette-color Office2019theme-buttonbackgroundbrush-dark"></div>|#000000|<div class="theme-palette-color Office2019theme-buttonbackgroundbrush-highcontrast"></div>|
|**CheckedForegroundBrush**|#FFFFFF|<div class="theme-palette-color Office2019theme-checkedforegroundbrush"></div>|#FFFFFF|<div class="theme-palette-color Office2019theme-checkedforegroundbrush-gray"></div>|#FFFFFF|<div class="theme-palette-color Office2019theme-checkedforegroundbrush-dark"></div>|#000000|<div class="theme-palette-color Office2019theme-checkedforegroundbrush-highcontrast"></div>|
|**DisabledBackgroundBrush**|#F1F1F1|<div class="theme-palette-color Office2019theme-disabledbackgroundbrush"></div>|#CBCBCB|<div class="theme-palette-color Office2019theme-disabledbackgroundbrush-gray"></div>|#3F3E3C|<div class="theme-palette-color Office2019theme-disabledbackgroundbrush-dark"></div>|#808080|<div class="theme-palette-color Office2019theme-disabledbackgroundbrush-highcontrast"></div>|
|**DisabledBorderBrush**|#D6D6D6|<div class="theme-palette-color Office2019theme-disabledborderbrush"></div>|#BEBEBE|<div class="theme-palette-color Office2019theme-disabledborderbrush-gray"></div>|#4F4F4F|<div class="theme-palette-color Office2019theme-disabledborderbrush-dark"></div>|#FFFFFF|<div class="theme-palette-color Office2019theme-disabledborderbrush-highcontrast"></div>|
|**HeaderBackgroundBrush**|#106EBE|<div class="theme-palette-color Office2019theme-headerbackgroundbrush"></div>|#106EBE|<div class="theme-palette-color Office2019theme-headerbackgroundbrush-gray"></div>|#106EBE|<div class="theme-palette-color Office2019theme-headerbackgroundbrush-dark"></div>|#37006E|<div class="theme-palette-color Office2019theme-headerbackgroundbrush-highcontrast"></div>|
|**HeaderForegroundBrush**|#FFFFFF|<div class="theme-palette-color Office2019theme-headerforegroundbrush"></div>|#FFFFFF|<div class="theme-palette-color Office2019theme-headerforegroundbrush-gray"></div>|#FFFFFF|<div class="theme-palette-color Office2019theme-headerforegroundbrush-dark"></div>|#FFFFFF|<div class="theme-palette-color Office2019theme-headerforegroundbrush-highcontrast"></div>|
|**HighlightedForegroundBrush**|#2F2F2F|<div class="theme-palette-color Office2019theme-highlightedforegroundbrush"></div>|#2F2F2F|<div class="theme-palette-color Office2019theme-highlightedforegroundbrush-gray"></div>|#2F2F2F|<div class="theme-palette-color Office2019theme-highlightedforegroundbrush-dark"></div>|#000000|<div class="theme-palette-color Office2019theme-highlightedforegroundbrush-highcontrast"></div>|
|**IconBrush**|#606060|<div class="theme-palette-color Office2019theme-iconbrush"></div>|#333333|<div class="theme-palette-color Office2019theme-iconbrush-gray"></div>|#A6A6A6|<div class="theme-palette-color Office2019theme-iconbrush-dark"></div>|#FFFFFF|<div class="theme-palette-color Office2019theme-iconbrush-highcontrast"></div>|
|**MainBackgroundBrush**|#FFFFFF|<div class="theme-palette-color Office2019theme-mainbackgroundbrush"></div>|#E2E2E2|<div class="theme-palette-color Office2019theme-mainbackgroundbrush-gray"></div>|#2F2F2F|<div class="theme-palette-color Office2019theme-mainbackgroundbrush-dark"></div>|#000000|<div class="theme-palette-color Office2019theme-mainbackgroundbrush-highcontrast"></div>|
|**MainBorderBrush**|#ACACAC|<div class="theme-palette-color Office2019theme-mainborderbrush"></div>|#A6A6A6|<div class="theme-palette-color Office2019theme-mainborderbrush-gray"></div>|#606060|<div class="theme-palette-color Office2019theme-mainborderbrush-dark"></div>|#FFFFFF|<div class="theme-palette-color Office2019theme-mainborderbrush-highcontrast"></div>|
|**MainForegroundBrush**|#000000|<div class="theme-palette-color Office2019theme-mainforegroundbrush"></div>|#000000|<div class="theme-palette-color Office2019theme-mainforegroundbrush-gray"></div>|#F1F1F1|<div class="theme-palette-color Office2019theme-mainforegroundbrush-dark"></div>|#FFFFFF|<div class="theme-palette-color Office2019theme-mainforegroundbrush-highcontrast"></div>|
|**MouseOverBackgroundBrush**|#C8C7C4|<div class="theme-palette-color Office2019theme-mouseoverbackgroundbrush"></div>|#ACACAC|<div class="theme-palette-color Office2019theme-mouseoverbackgroundbrush-gray"></div>|#B3AFAD|<div class="theme-palette-color Office2019theme-mouseoverbackgroundbrush-dark"></div>|#1AEBFF|<div class="theme-palette-color Office2019theme-mouseoverbackgroundbrush-highcontrast"></div>|
|**PressedBackgroundBrush**|#B3AFAD|<div class="theme-palette-color Office2019theme-pressedbackgroundbrush"></div>|#918E8D|<div class="theme-palette-color Office2019theme-pressedbackgroundbrush-gray"></div>|#767676|<div class="theme-palette-color Office2019theme-pressedbackgroundbrush-dark"></div>|#1AEBFF|<div class="theme-palette-color Office2019theme-pressedbackgroundbrush-highcontrast"></div>|
|**ReadOnlyBackgroundBrush**|#FFFFFF|<div class="theme-palette-color Office2019theme-readonlybackgroundbrush"></div>|#E2E2E2|<div class="theme-palette-color Office2019theme-readonlybackgroundbrush-gray"></div>|#2F2F2F|<div class="theme-palette-color Office2019theme-readonlybackgroundbrush-dark"></div>|#008000|<div class="theme-palette-color Office2019theme-readonlybackgroundbrush-highcontrast"></div>|
|**ReadOnlyBorderBrush**|#ACACAC|<div class="theme-palette-color Office2019theme-readonlyborderbrush"></div>|#A6A6A6|<div class="theme-palette-color Office2019theme-readonlyborderbrush-gray"></div>|#606060|<div class="theme-palette-color Office2019theme-readonlyborderbrush-dark"></div>|#FFFFFF|<div class="theme-palette-color Office2019theme-readonlyborderbrush-highcontrast"></div>|
|**SecondaryBackgroundBrush**|#D6D5D5|<div class="theme-palette-color Office2019theme-secondarybackgroundbrush"></div>|#B6B3B1|<div class="theme-palette-color Office2019theme-secondarybackgroundbrush-gray"></div>|#2B2B2B|<div class="theme-palette-color Office2019theme-secondarybackgroundbrush-dark"></div>|#37006E|<div class="theme-palette-color Office2019theme-secondarybackgroundbrush-highcontrast"></div>|
|**SecondaryForegroundBrush**|#000000|<div class="theme-palette-color Office2019theme-secondaryforegroundbrush"></div>|#FFFFFF|<div class="theme-palette-color Office2019theme-secondaryforegroundbrush-gray"></div>|#F1F1F1|<div class="theme-palette-color Office2019theme-secondaryforegroundbrush-dark"></div>|#FFFFFF|<div class="theme-palette-color Office2019theme-secondaryforegroundbrush-highcontrast"></div>|
|**ValidationBrush**|#E43E00|<div class="theme-palette-color Office2019theme-validationbrush"></div>|#E43E00|<div class="theme-palette-color Office2019theme-validationbrush-gray"></div>|#E43E00|<div class="theme-palette-color Office2019theme-validationbrush-dark"></div>|#EB0300|<div class="theme-palette-color Office2019theme-validationbrush-highcontrast"></div>|

> The newly introduced brushes and their colors for each variation follow. They are available after the **R3 2021**.

|Brush name|   |Light|   |Gray|   |Dark|   |HighContrast|
|----------|---|-----|---|----|---|----|---|----|
|**DisabledCheckedForegroundBrush**|#FFFFFF|<div class="theme-palette-color Office2019theme-disabledcheckedforegroundbrush"></div>|#FFFFFF|<div class="theme-palette-color Office2019theme-disabledcheckedforegroundbrush-gray"></div>|#FFFFFF|<div class="theme-palette-color Office2019theme-disabledcheckedforegroundbrush-dark"></div>|#808080|<div class="theme-palette-color Office2019theme-disabledcheckedforegroundbrush-highcontrast"></div>|
|**DisabledForegroundBrush**|#000000|<div class="theme-palette-color Office2019theme-disabledforegroundbrush"></div>|#000000|<div class="theme-palette-color Office2019theme-disabledforegroundbrush-gray"></div>|#F1F1F1|<div class="theme-palette-color Office2019theme-disabledforegroundbrush-dark"></div>|#00FF00|<div class="theme-palette-color Office2019theme-disabledforegroundbrush-highcontrast"></div>|
|**DisabledIconBrush**|#606060|<div class="theme-palette-color Office2019theme-disablediconbrush"></div>|#333333|<div class="theme-palette-color Office2019theme-disablediconbrush-gray"></div>|#A6A6A6|<div class="theme-palette-color Office2019theme-disablediconbrush-dark"></div>|#00FF00|<div class="theme-palette-color Office2019theme-disablediconbrush-highcontrast"></div>|
|**IconWrapperBrush**|transparent|<div class="theme-palette-color Office2019theme-iconwrapperbrush"></div>|transparent|<div class="theme-palette-color Office2019theme-iconwrapperbrush-gray"></div>|transparent|<div class="theme-palette-color Office2019theme-iconwrapperbrush-dark"></div>|#000000|<div class="theme-palette-color Office2019theme-iconwrapperbrush-highcontrast"></div>|
|**SelectedUnfocusedBackgroundBrush**|#E5E5E5|<div class="theme-palette-color Office2019theme-selectedunfocusedbackgroundbrush"></div>|#BFBFBF|<div class="theme-palette-color Office2019theme-selectedunfocusedbackgroundbrush-gray"></div>|#3D3D3D|<div class="theme-palette-color Office2019theme-selectedunfocusedbackgroundbrush-dark"></div>|#808080|<div class="theme-palette-color Office2019theme-selectedunfocusedbackgroundbrush-highcontrast"></div>|
|**TertiaryBackgroundBrush**|#F1F1F1|<div class="theme-palette-color Office2019theme-tertiarybackgroundbrush"></div>|#CBCBCB|<div class="theme-palette-color Office2019theme-tertiarybackgroundbrush-gray"></div>|#3C3C3C|<div class="theme-palette-color Office2019theme-tertiarybackgroundbrush-dark"></div>|#37006E|<div class="theme-palette-color Office2019theme-tertiarybackgroundbrush-highcontrast"></div>|

We have also introduced some control-specific brushes for the:
* RadBulletGraph - ComparativeMeasureBrush, QualityGoodBrush, QualityPoorBrush and QualitySatisfactoryBrush
* RadTimeBar - TimeBarSelectionBorderBrush
* RadTimeline - TimelineInstantItemBrush and TimelineItemBrush

More information about each brush follows in the next topic.


#### __Figure 1: Theme colors represented in RadOutlookBar__
![Office2019 theme colors represented in RadOutlookBar](images/Office2019-theme-outlook.PNG)	

## Office2019Palette Properties

### Accent Brushes

* **AccentBackgroundBrush**: Used for the background of the elements that should have accent - e.g. the background of the toggle button in its checked state.
* **AccentBorderBrush**:Used for the border color of the elements that should have accent - e.g. the border color of the toggle button in its checked state. 
* **AccentMouseOverBackgroundBrush**: Used for the background of the accent elements in their mouse over state (e.g. all buttons except the ones in the RadRibbonView).
* **AccentMouseOverBorderBrush**: Used for the border color of the accent elements in their mouse over state (e.g. all buttons except the ones in the RadRibbonView).
* **AccentPressedBackgroundBrush**: Used for the background of the accent elements in their pressed state (e.g. all buttons except the ones in the RadRibbonView). Also used for the buttons, toggling dropdown menus (opened state).

### Foreground Brushes 

* **MainForegroundBrush**: This is the default foreground of the theme.
* **SecondaryForegroundBrush**: Used for the foreground of the elements, placed over a background that would otherwise require reverting the default foreground - e.g. the BaseBackgroundBrush. It could be used as a default foreground to controls like the MS CheckBox, RadioButton, GroupBox in such scenarios. May also be considered for buttons with IsBackgroundVisible="False".
* **HighlightedForegroundBrush**: Used for the foreground of the elements when their parent is highlighted/hovered, pressed or selected/checked and hovered at once.
* **CheckedForegroundBrush**: Used for the foreground of the elements when their parent is in its selected/checked state.
* **HeaderForegroundBrush**: Used for the foreground of the header elements in a Window-based controls (e.g. RadWindow, RadTabbedWindow, FileDialogs, etc.).
* **IconBrush**: Used for the default foreground of the RadGlyph icons.

### Base Brushes 

* **BaseBackgroundBrush**: This is the recommended background to be used as an application background with this theme. It is also used as a background of the RadRichTextBox, RadSpreadsheet and RadPdfViewer controls. 
* **MainBackgroundBrush**: Used for the background the inputs and other editable elements such as RadAutocompleteBox, the content of their dropdowns/popup menus, and some child control elements like RadTaskBoard’s card, RadTileList’s tile, etc.
* **MainBorderBrush**: This is the default border color of all controls.
* **SecondaryBackgroundBrush**: Used for the background of non-editable, secondary elements - e.g. the RadCalculator's alternate buttons. Also used for the default background of the RadProgressBar's track and the RadSlider. 
* **AlternativeBackgroundBrush**: Used for the background of the RadMenu, RadOutlookBar, RadSpreadsheet specific child-controls and the footer background of its dialogs, RadRibbonView's tabs background, RadGridView's panels background (GroupPanel, SearchPanel), alternation rows background, etc. 
* **ButtonBackgroundBrush**: This is the default background of all buttons.
* **HeaderBackgroundBrush**: Used for the background of the header elements in a Window-based controls (e.g. RadWindow, RadTabbedWindow, FileDialogs, etc.).
* **MouseOverBackgroundBrush**: Used for the background of the non-accent elements in their mouse over state - e.g. the background of the RadRibbonView's buttons.
* **PressedBackgroundBrush**: Used for the background of the non-accent elements in their pressed state - e.g. the background of the RadRibbonView's buttons.
* **TertiaryBackgroundBrush**: Used for the background of the chat control's TextMessageControl and the gantt view control's SpecialSlots. 

> The **TertiaryBackgroundBrush** is not available with versions prior to the **R3 2021** release of the UI for WPF suite.

### Special State Brushes

* **DisabledBackgroundBrush**: Used for the background of the controls in their disabled state.
* **DisabledBorderBrush**: Used for the border color of the controls in their disabled state.
* **DisabledCheckedForegroundBrush**: Used for the foreground of the elements in their disabled and checked state (RadGlyph icons included).
* **DisabledForegroundBrush**: Used for the foreground of the elements in their disabled state. 
* **DisabledIconBrush**: Used for the foreground of the RadGlyph icons in their disabled state.
* **IconWrapperBrush**: Used as a wrapper background for the images/icons when their color/foreground conflicts with the background of their parent in its mouse over state. This brush is introduced mainly for the HighContrast color variation. Its color is transparent in the other color variations. 
* **ReadOnlyBackgroundBrush**: Used for the background of the controls in their read-only state.
* **ReadOnlyBorderBrush**: Used for the border color of the controls in their read-only state.
* **SelectedUnfocusedBackgroundBrush**: Used for the background of the elements in their selected and not focused state (e.g., the GridViewRow, TreeListViewRow and the TreeViewItem). 
* **ValidationBrush**: Used for the background/border color of the controls to indicate the validation errors - for the foreground of the invalid control, or as a border for the error tooltip, border for invalid rows and cells.

> The **DisabledCheckedForegroundBrush**, **DisabledForegroundBrush**, **DisabledIconBrush**, **IconWrapperBrush** and **SelectedUnfocusedBackgroundBrush** are not available with versions prior to the **R3 2021** release of the UI for WPF suite.

### Control Specific Brushes

* **ComparativeMeasureBrush**: Used in the BulletGraph control as a value of the ComparativeMeasureBrush property. 
* **QualityGoodBrush**: Used in the BulletGraph control as a value of the QualityGoodBrush property.
* **QualityPoorBrush**: Used in the BulletGraph control as a value of the QualityPoorBrush property.
* **QualitySatisfactoryBrush**: Used in the BulletGraph control as a value of the QualitySatisfactoryBrush property.
* **TimeBarSelectionBorderBrush**: Used for border color of the SelectionThumbHandle and the SelectionRange elements in the TimeBar control. 
* **TimelineInstantItemBrush**: Used for the background of the TimelineInstantItem (in the TimelineInstantItemControlStyle). 
* **TimelineItemBrush**: Used for the background of the TimelineItem (in the TimelineItemControlStyle). 

> All of the above brushes are not available with versions prior to the **R3 2021** release of the UI for WPF suite.

### Other Properties

* **DisabledOpacity**: Used for the controls in their **disabled** state.
* **HeaderBorderThickness**: Used for wrapping header elements with a border. Introduced mainly for the HighContrast color variation for which it has value 1. For all other color variations its default value is 0. Also used for the tab control's items in their mouse over state.
* **ReadOnlyOpacity**: Used for the controls in their **read-only** state.
* **FocusThickness**: Used for the thickness of the focus border of the buttons. It is of type **Thickness** and its default value is 2, 2, 2, 2.

> The **HeaderBorderThickness** is not available with versions prior to the **R3 2021** release of the UI for WPF suite.

## Theme Variation Changing

The Office2019 theme comes with three color variations, inspired by the colors used in MS Office. The **Light** variation corresponds to Microsoft's Colorful Office theme, the **Gray** - to the Dark Gray Office theme and the **Dark** - to the Black Office theme. The following example demonstrates the ability to switch between the supported **Light**, **Gray**, **Dark** and **HighContrast** color palettes by calling the **LoadPreset()** method as shown below:

#### __[C#] Example 1: Changing the color variation of the theme__
{{region cs-styling-appearance-Office2019-theme-1}}
	//default color variation 
	Office2019Palette.LoadPreset(Office2019Palette.ColorVariation.Light);   
	
	//Gray color variation 
	Office2019Palette.LoadPreset(Office2019Palette.ColorVariation.Gray);   
	
	//Dark color variation 
	Office2019Palette.LoadPreset(Office2019Palette.ColorVariation.Dark);

	//HighContrast color variation 
	Office2019Palette.LoadPreset(Office2019Palette.ColorVariation.HighContrast);  
{{endregion}}

#### __Figure 2: Office2019 theme color variations__
![Office2019 theme colors represented in RadTaskBoard](images/Office2019-theme-variations.PNG)

>important All variations of the theme are designed with a specific background in mind and it is recommended to use such a background in your application when working with it - it is represented by the theme palette's **BaseBackgroundBrush**.

## Font Family and Font Size

When using the **Office2019 theme**, the **FontSize** and **FontFamily** properties of all components in the application can be dynamically changed the same way as in the **Windows8**, **Windows8Touch**, **Office2013**, **VisualStudio2013**, **Office2016**, **Green**, **Material**, **Fluent**,**Crystal** and **VisualStudio2019** themes.

The **FontSize** and **FontFamily** properties are public - they can easily be modified at a single point. The most commonly used font size in the theme is with value **12** and can be modified through the **Office2019Palette.Palette.FontSize** property in the same manner as in the other themes that support a theme palette. 

The default font used in the theme is **Segoe UI**.

>important For complex scenarios it is strongly recommend to set the **FontSize** properties **only before the application is initialized**. 

__Example 2__ shows the default font sizes and families.

#### __[C#] Example 2: Default FontSize__
{{region cs-styling-appearance-Office2019-theme-2}}
	Office2019Palette.Palette.FontSize = 12;
	Office2019Palette.Palette.FontSizeS = 13;
	Office2019Palette.Palette.FontSizeM = 14;
	Office2019Palette.Palette.FontSizeL = 16;
{{endregion}}

__Example 3__ shows how to change the default FontFamily from "Segoe UI" to "Calibri Italic" and the FontSize from 12 to 18.

#### __[C#] Example 3: Changing the theme's FontSize and FontFamily__
{{region cs-styling-appearance-Office2019-theme-2}}
	private void OnButtonChangeFontSizeClick(object sender, RoutedEventArgs e)
	{
		Office2019Palette.Palette.FontSize = 18;
		Office2019Palette.Palette.FontFamily = new FontFamily("Calibri Italic");
	}
{{endregion}}

#### __Figure 3: Setting FontSize and FontFamily__
![RadCalendar with modified FontSize and FontFamily](images/Office2019-theme-calendar-font-change.png)	

## Glyphs

The **Office2019 Theme** also uses the **Telerik Web UI** [font glyphs](({%slug common-styling-appearance-glyphs-overview%})) by default. The **RadGlyph** provides a lightweight, flexible and design-time-friendly implementation of our glyph font.  

> You can read more about the RadGlyph in the [RadGlyph Overview article]({%slug common-styling-appearance-radglyph%}) and about the range of the font glyphs in the [Font Glyphs Overview article]({%slug common-styling-appearance-glyphs-reference-sheet%}).

## Theme Helper

The [ThemeHelper]({%slug styling-appearance-theme-helper%}) class that comes with the **R3 2019** release is used in the Office2019 theme. It exposes a set of attached properties and can be used to directly modify the appearance of a specific basic control without the need to alter its control template.

**Example 4** shows a **RadToggleButton** control with modified brushes for its different states through the **ThemeHelper** class:

#### __[XAML] Example 4: Set RadToggleButton's visual appearance through the ThemeHelper class__
{{region xaml-styling-appearance-Office2019-theme-3}}
	<telerik:RadToggleButton Content="RadToggleButton" 
							 Margin="10"
							 xmlns:helpers="clr-namespace:Telerik.Windows.Controls.Theming.Helpers;assembly=Telerik.Windows.Controls"
							 helpers:ThemeHelper.MouseOverBrush="{telerik:Office2019Resource ResourceKey=AccentMouseOverBrush}"
							 helpers:ThemeHelper.PressedBrush="{telerik:Office2019Resource ResourceKey=ValidationBrush}"
							 helpers:ThemeHelper.CheckedBrush="{telerik:Office2019Resource ResourceKey=AccentMainBrush}"/>
{{endregion}}

#### **Figure 4: Appearance of the RadToggleButton in the different states**  
![RadToggleButton States](images/Office2019-theme-togglebutton-states.png)

## Changing Opacity 

If you need to change the opacity of the disabled and read-only elements, you can easily do so by using the __DisabledOpacity__ and __ReadOnlyOpacity__ properties of the Office2019Palette. The default values are **0.3** and **0.6** respectively. 

#### __[C#] Example 5: Changing the opacity__		
{{region cs-styling-appearance-Office2019-theme-4}}
	Office2019Palette.Palette.DisabledOpacity = 0.5;
	Office2019Palette.Palette.ReadOnlyOpacity = 0.5;
{{endregion}}

## Setting White Color Variation

The theme has a few built-in [color variations](#theme-variation-changing) - Light, Gray and Dark. You can customize the Light variation and make it look like Microsoft's White Office Theme by changing several color properties of the [theme palette](#office2019palette-properties).

To achieve this, first ensure that the Light [variation](#theme-variation-changing) is applied. This is the default one, so no explicit actions are required here. Then, set the following color properties:

#### __[C#] Example 6: Applying palette colors__		
{{region cs-styling-appearance-Office2019-theme-5}}
	Office2019Palette.Palette.ButtonBackgroundColor = (Color)ColorConverter.ConvertFromString("#FFFFFF");
	Office2019Palette.Palette.BaseBackgroundColor = (Color)ColorConverter.ConvertFromString("#FFFFFF");
	Office2019Palette.Palette.AlternativeBackgroundColor = (Color)ColorConverter.ConvertFromString("#FAFAFA");
	Office2019Palette.Palette.SecondaryBackgroundColor = (Color)ColorConverter.ConvertFromString("#F1F1F1");
{{endregion}}

## See Also  
 * [Setting a Theme (Using  Implicit Styles)]({%slug styling-apperance-implicit-styles-overview%})
 * [Style Manager]({%slug common-styling-apperance-setting-theme-wpf%})
 * [Glyphs Overview]({%slug common-styling-appearance-glyphs-overview%})
 * [Office2016 Theme]({%slug common-styling-appearance-office2016-theme%})
