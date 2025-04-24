<h3>Static Personal Website | AWS EC2, IAM, WordPress (July 2024)</h3>
<ul>
  <li>Hosted WordPress site on EC2 with secure IAM setup.</li>
  <li>Assigned Elastic IP for persistent access.</li>
</ul>

<style>
  .carousel-wrapper {
    overflow: hidden;
    width: 100%;
    margin: 20px 0;
    border-radius: 6px;
  }

  .carousel {
    display: flex;
    animation: scroll 12s linear infinite;
    gap: 10px;
  }

  .carousel img {
    height: 180px;
    width: auto;
    border-radius: 4px;
    border: 1px solid #00ff00;
    box-shadow: 0 0 5px #00ff00;
  }

  @keyframes scroll {
    0%   { transform: translateX(0%); }
    33%  { transform: translateX(-100%); }
    66%  { transform: translateX(-200%); }
    100% { transform: translateX(0%); }
  }
</style>

<div class="carousel-wrapper">
  <div class="carousel">
    <img src="assets/img/1.jpg" alt="Screenshot 1" />
    <img src="assets/img/2.jpg" alt="Screenshot 2" />
    <img src="assets/img/3.jpg" alt="Screenshot 3" />
  </div>
</div>
