---
title: Functions > Count
category: Tags
order: 4
---

Returns the number of instances of a given repeater, or evaluates a ternary expression using the number of instances.

## Syntax

&lt;&lt;[**Count**:Repeater:Expression]&gt;&gt; <span class="badge platform">Server</span>

#### Repeater <span class="badge platform">Required</span>
Tag name of repeater

#### Expression
Ternary expression using **@Count** to reference count e.g. @Count > 1 ? &apos;Contacts&apos; : &apos;Contact&apos;]&gt;&gt;

## Examples

|Function|Result|
|---|---|
|&lt;&lt;[Count:Contact]&gt;&gt;|2|
|&lt;&lt;[Count:Contact:@Count > 1 ? &apos;Contacts&apos; : &apos;Contact&apos;]&gt;&gt;|Contacts|