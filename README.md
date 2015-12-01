# lint_tools_ios
all in one place for all iOS lint tools

============
# Integrated
* SwiftLint
* StoryboardLint

# Usage
1. Add a new build phase for your target
2. Add lint tools you need, be careful when you have too many lint errors, because it will fail your build. :)

```
./lint-tools-ios swift_lint

```
and

```
./lint-tools-ios storyboard_lint .

```
**Note: It's recommended to have different lint tools in different build phases**


Checkout the image attached
![Usage](./lint-tools-usage.png)



# Future plans
Working in progress

# Contribute
pull requests welcomed, any ideas/questions please don't hesitate to contact qinhan@xingshulin.com

# We are recruting...