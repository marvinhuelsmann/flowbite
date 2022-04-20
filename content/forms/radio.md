---
layout: home
title: Tailwind CSS Radio - Flowbite
description: Use the Tailwind CSS form and input elements such as checkboxes, radios, textarea, text inputs to collect information from users with Flowbite
group: forms
toc: true

previous: Textarea
previousLink: forms/textarea/
next: Radio
nextLink: forms/radio/
---

## Checkbox example

{{< example class="dark:bg-gray-800" github="components/forms.md" show_dark=true >}}
<div class="flex items-center mb-4">
    <input id="default-radio-1" type="radio" value="" name="default-radio" class="w-4 h-4 text-blue-600 bg-gray-100 border-gray-300 focus:ring-blue-500 dark:focus:ring-blue-600 dark:ring-offset-gray-800 focus:ring-2 dark:bg-gray-700 dark:border-gray-600">
    <label for="default-radio-1" class="ml-2 text-sm font-medium text-gray-900 dark:text-gray-300">Default radio</label>
</div>
<div class="flex items-center">
    <input checked id="default-radio-2" type="radio" value="" name="default-radio" class="w-4 h-4 text-blue-600 bg-gray-100 border-gray-300 focus:ring-blue-500 dark:focus:ring-blue-600 dark:ring-offset-gray-800 focus:ring-2 dark:bg-gray-700 dark:border-gray-600">
    <label for="default-radio-2" class="ml-2 text-sm font-medium text-gray-900 dark:text-gray-300">Checked state</label>
</div>
{{< /example >}}

## Disabled state

{{< example class="dark:bg-gray-800" github="components/forms.md" show_dark=true >}}
<div class="flex items-center mb-4">
    <input disabled id="disabled-radio-1" type="radio" value="" name="disabled-radio" class="w-4 h-4 text-blue-600 bg-gray-100 border-gray-300 focus:ring-blue-500 dark:focus:ring-blue-600 dark:ring-offset-gray-800 focus:ring-2 dark:bg-gray-700 dark:border-gray-600">
    <label for="disabled-radio-1" class="ml-2 text-sm font-medium text-gray-400 dark:text-gray-500">Disabled radio</label>
</div>
<div class="flex items-center">
    <input disabled checked id="disabled-radio-2" type="radio" value="" name="disabled-radio" class="w-4 h-4 text-blue-600 bg-gray-100 border-gray-300 focus:ring-blue-500 dark:focus:ring-blue-600 dark:ring-offset-gray-800 focus:ring-2 dark:bg-gray-700 dark:border-gray-600">
    <label for="disabled-radio-2" class="ml-2 text-sm font-medium text-gray-400 dark:text-gray-500">Disabled checked</label>
</div>
{{< /example >}}

## Checkbox link

{{< example class="dark:bg-gray-800" github="components/forms.md" show_dark=true >}}
<div class="flex items-center">
    <input id="link-radio" type="radio" value="" class="w-4 h-4 text-blue-600 bg-gray-100 border-gray-300 focus:ring-blue-500 dark:focus:ring-blue-600 dark:ring-offset-gray-800 focus:ring-2 dark:bg-gray-700 dark:border-gray-600">
    <label for="link-radio" class="ml-2 text-sm font-medium text-gray-900 dark:text-gray-300">Radio button with a <a href="#" class="text-blue-600 dark:text-blue-500 hover:underline">link inside</a>.</label>
</div>
{{< /example >}}

## Helper text

{{< example class="dark:bg-gray-800" github="components/forms.md" show_dark=true >}}
<div class="flex">
    <div class="flex items-center h-5">
        <input id="helper-radio" aria-describedby="helper-radio-text" type="radio" value="" class="w-4 h-4 text-blue-600 bg-gray-100 border-gray-300 focus:ring-blue-500 dark:focus:ring-blue-600 dark:ring-offset-gray-800 focus:ring-2 dark:bg-gray-700 dark:border-gray-600">
    </div>
    <div class="ml-2 text-sm">
        <label for="helper-radio" class="font-medium text-gray-900 dark:text-gray-300">Free shipping via Flowbite</label>
        <p id="helper-radio-text" class="text-xs font-normal text-gray-500 dark:text-gray-300">For orders shipped from $25 in books or $29 in other categories</p>
    </div>
</div>
{{< /example >}}

## Inline

{{< example class="dark:bg-gray-800" github="components/forms.md" show_dark=true >}}
<div class="flex">
    <div class="flex items-center mr-4">
        <input id="inline-radio" type="radio" value="" name="inline-radio-group" class="w-4 h-4 text-blue-600 bg-gray-100 border-gray-300 focus:ring-blue-500 dark:focus:ring-blue-600 dark:ring-offset-gray-800 focus:ring-2 dark:bg-gray-700 dark:border-gray-600">
        <label for="inline-radio" class="ml-2 text-sm font-medium text-gray-900 dark:text-gray-300">Inline 1</label>
    </div>
    <div class="flex items-center mr-4">
        <input id="inline-2-radio" type="radio" value="" name="inline-radio-group" class="w-4 h-4 text-blue-600 bg-gray-100 border-gray-300 focus:ring-blue-500 dark:focus:ring-blue-600 dark:ring-offset-gray-800 focus:ring-2 dark:bg-gray-700 dark:border-gray-600">
        <label for="inline-2-radio" class="ml-2 text-sm font-medium text-gray-900 dark:text-gray-300">Inline 2</label>
    </div>
    <div class="flex items-center mr-4">
        <input checked id="inline-checked-radio" type="radio" value="" name="inline-radio-group" class="w-4 h-4 text-blue-600 bg-gray-100 border-gray-300 focus:ring-blue-500 dark:focus:ring-blue-600 dark:ring-offset-gray-800 focus:ring-2 dark:bg-gray-700 dark:border-gray-600">
        <label for="inline-checked-radio" class="ml-2 text-sm font-medium text-gray-900 dark:text-gray-300">Inline checked</label>
    </div>
    <div class="flex items-center">
        <input disabled id="inline-disabled-radio" type="radio" value="" name="inline-radio-group" class="w-4 h-4 text-blue-600 bg-gray-100 border-gray-300 focus:ring-blue-500 dark:focus:ring-blue-600 dark:ring-offset-gray-800 focus:ring-2 dark:bg-gray-700 dark:border-gray-600">
        <label for="inline-disabled-radio" class="ml-2 text-sm font-medium text-gray-400 dark:text-gray-500">Inline disabled</label>
    </div>
</div>
{{< /example >}}

## Colors

{{< example class="dark:bg-gray-800" github="components/forms.md" show_dark=true >}}
<div class="flex flex-wrap">
    <div class="flex items-center mr-4">
        <input id="red-radio" type="radio" value="" name="colored-radio" class="w-4 h-4 text-red-600 bg-gray-100 border-gray-300 focus:ring-red-500 dark:focus:ring-red-600 dark:ring-offset-gray-800 focus:ring-2 dark:bg-gray-700 dark:border-gray-600">
        <label for="red-radio" class="ml-2 text-sm font-medium text-gray-900 dark:text-gray-300">Red radio</label>
    </div>
    <div class="flex items-center mr-4">
        <input id="green-radio" type="radio" value="" name="colored-radio" class="w-4 h-4 text-green-600 bg-gray-100 border-gray-300 focus:ring-green-500 dark:focus:ring-green-600 dark:ring-offset-gray-800 focus:ring-2 dark:bg-gray-700 dark:border-gray-600">
        <label for="green-radio" class="ml-2 text-sm font-medium text-gray-900 dark:text-gray-300">Green radio</label>
    </div>
    <div class="flex items-center mr-4">
        <input checked id="purple-radio" type="radio" value="" name="colored-radio" class="w-4 h-4 text-purple-600 bg-gray-100 border-gray-300 focus:ring-purple-500 dark:focus:ring-purple-600 dark:ring-offset-gray-800 focus:ring-2 dark:bg-gray-700 dark:border-gray-600">
        <label for="purple-radio" class="ml-2 text-sm font-medium text-gray-900 dark:text-gray-300">Purple radio</label>
    </div>
    <div class="flex items-center mr-4">
        <input id="teal-radio" type="radio" value="" name="colored-radio" class="w-4 h-4 text-teal-600 bg-gray-100 border-gray-300 focus:ring-teal-500 dark:focus:ring-teal-600 dark:ring-offset-gray-800 focus:ring-2 dark:bg-gray-700 dark:border-gray-600">
        <label for="teal-radio" class="ml-2 text-sm font-medium text-gray-900 dark:text-gray-300">Teal radio</label>
    </div>
    <div class="flex items-center mr-4">
        <input id="yellow-radio" type="radio" value="" name="colored-radio" class="w-4 h-4 text-yellow-400 bg-gray-100 border-gray-300 focus:ring-yellow-500 dark:focus:ring-yellow-600 dark:ring-offset-gray-800 focus:ring-2 dark:bg-gray-700 dark:border-gray-600">
        <label for="yellow-radio" class="ml-2 text-sm font-medium text-gray-900 dark:text-gray-300">Yellow radio</label>
    </div>
</div>
{{< /example >}}