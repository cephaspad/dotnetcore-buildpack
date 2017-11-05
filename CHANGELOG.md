# .NET Core Buildpack Changelog

## 2017-11-04
Folked from jincod

## 2017-11-04

- Removed `dotnet restore` step because it is run implicitly as part of `dotnet publish`
- Extremely optimized slag size (`DOTNET_SKIP_FIRST_TIME_EXPERIENCE:1`)
- Updated .NET Core SDK 2.0.2

## 2017-11-03

- Added support `PROJECT_FILE` and `PROJECT_NAME` environment variables ([#23](https://github.com/vnpadkids/dotnetcore-buildpack/pull/23))