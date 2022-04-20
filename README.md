# bootstrap5-tooltip-css
Bootstrap 5: Customizing Tooltip

Want to customize Bootstrap 5 tooltip? Here are the CSS you need to do so.

.tooltip-inner {
    background-color: #00ff00;
    box-shadow: 0px 0px 8px #ff0000;
    color: #0000ff;
  }
.tooltip.bs-tooltip-top     .tooltip-arrow::before { border-top-color:    #00ff00; }
.tooltip.bs-tooltip-bottom  .tooltip-arrow::before { border-bottom-color: #00ff00; }
.tooltip.bs-tooltip-start   .tooltip-arrow::before { border-left-color:   #00ff00; }
.tooltip.bs-tooltip-end     .tooltip-arrow::before { border-right-color:  #00ff00; }
