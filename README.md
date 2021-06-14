# css-circles

<svg fill="none" viewBox="0 0 400 400" width="400" height="400" xmlns="http://www.w3.org/2000/svg">
    <foreignObject width="100%" height="100%">
        <div xmlns="http://www.w3.org/1999/xhtml">
            <style>
.bars,
.bars:before,
.bars:after {
  background: var(--fill-color);
  -webkit-animation: load1 1s infinite ease-in-out;
  animation: load1 1s infinite ease-in-out;
  width: .5em;
  top: 25px;
}

.bars {
  color: #000;
  text-indent: -9999em;
  margin: 0 auto;
  position: relative;
  font-size: 11px;
  -webkit-transform: translateZ(0);
  -ms-transform: translateZ(0);
  transform: translateZ(0);
  -webkit-animation-delay: -0.16s;
  animation-delay: -0.16s;
}

.bars:before,
.bars:after {
  position: absolute;
  top: 0;
  content: '';
}

.bars:before {
  left: -.7em;
  -webkit-animation-delay: -0.32s;
  animation-delay: -0.32s;
}

.bars:after {
  left: .7em;
}
            </style>
          <div class='bars'></div>
        </div>
    </foreignObject>
</svg>
