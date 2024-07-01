body {
  background-color: #000;
  overflow: hidden;
}

.particles {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
}

.particle {
  position: absolute;
  background-color: #fff;
  border-radius: 50%;
  animation: float 10s infinite;
}

@keyframes float {
  0%, 100% {transform: translateY(0);}
  50% {transform: translateY(-100px);}
}
