# EigenCocoa

## Quickstart

Simply include this pod in your `Podfile` for any OSX target:
```
pod 'EigenCocoa', '~> 3.4.0'
```

Then, in any C++ *or Objective C++* file, include Eigen headers: 
```
#include <Eigen/Core>
#include <Eigen/Geometry>
#include <Eigen/LU>
```

## Summary

This repo contains a [CocoaPod](https://cocoapods.org/) wrapper for the c++ 
[Eigen](http://eigen.tuxfamily.org/index.php) project, which provides a
pop header-only matrix library.  This Pod restricts to the MPL-only
portion of Eigen, excluding the GPL bits.

Note that the license used in this repo is independent of that used in
Eigen, which currently has a [mixed license](https://gitlab.com/libeigen/eigen/-/blob/master/COPYING.README).

See also the (outdated) [official Eigen pod](https://cocoapods.org/pods/eigen).

## Development

This repo contains a single Podspec file.  To modify, just edit the 
Podspect and use `pod repo push MyRepo Eigen
Cocoa.podspec.json --verbose`.
