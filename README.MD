* Which model has a lower loss?
    * Model that uses closing prices has lower loss for each window size

* Which model tracks the actual values better over time?
    * Model that uses closing prices tracks the acual value better.

* Which window size works best for the model?
    * For FNG, and closing price the closing price an optimal window is different. For FNG, `window_size=5` is optimal, while for closing price `window_size=7` is optimal 