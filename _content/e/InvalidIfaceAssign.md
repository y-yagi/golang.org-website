---
title: InvalidIfaceAssign
layout: article
---
<!-- Copyright 2023 The Go Authors. All rights reserved.
     Use of this source code is governed by a BSD-style
     license that can be found in the LICENSE file. -->

<!-- Code generated by generrordocs.go; DO NOT EDIT. -->

```
InvalidIfaceAssign occurs when a value of type T is used as an
interface, but T does not implement a method of the expected interface.

Example:
 type I interface {
 	f()
 }

 type T int

 var x I = T(1)
```

