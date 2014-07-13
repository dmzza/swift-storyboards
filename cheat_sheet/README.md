# Cheat Sheet

## Definitions
 - Outlet
  - A variable to reference a view in code.
 - Action
  - An instance method triggered by tapping or interacting with a view.
 - Constraint (Auto-Layout, optional)
  - A relationship between two views, or a dimension of one view, ordered by priority.
  - Each view should have at least 4 constraints (ie: width, height, distance from bottom of super view, and horizontally centered)
 - Size Class (Adaptive design, optional)
  - Apps should be designed to fit arbitrary screen dimensions and orientations. Size classes come in compact and regular modes for width and height.
![enable auto-layout and size classes](https://developer.apple.com/library/prerelease/ios/recipes/xcode_help-IB_adaptive_sizes/art/sc_enable_size_classes_2x.png)



## Interface
 - Split-view
  - see the storyboard and the related swift file at the same time
![split view](http://i.imgur.com/mHebgqu.png)
 - control-drag:
  - create an outlet: drag from any view to the top of the related swift file
  - create an action in the same way for any interactive view
  - create an auto-layout constraint between two views

 - option-drag:
  - replicated the selected object and place it

