# RetainedDateTimePickers
Android Library to help you with your date & time pickers while retaining the instance of the pickers on orientation change. — Edit

# Installation

#### Gradle
```groovy
    compile 'coming soon'
```

#### Maven
```xml
    <coming soon/>
```

Usage
=====

Your `Activity` must implement `DatePickerCallback` or and `TimePickerCallback` to receive the selected date & time.


> **To understand more how the library works, please take a look at the sample app.**

# Why this library?

* DatePickerDialog & TimePickerDialog are not retained on orientation change, you'd do a lot of work to retain them, this library simplify that.
* Its simple to use.
* Its Customizable(Support Custom Themes). 
* Minimum API is 16, but it'll probably work in API 9 and above, just make sure you test it out (we use `Support Fragment`).  

# Dependency

Android Support Fragment Library ``v24.2.1``

# Copyright Notice

Copyright (C) 2016 Kosh.
Licensed under the [Apache 2.0](http://www.apache.org/licenses/LICENSE-2.0)
license (see the LICENSE file).
