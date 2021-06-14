HI! I'm Razaol Karim
@@ -0,0 +1,210 @@
<svg fill="none" viewBox="0 0 854 140" width="854" height="140" xmlns="http://www.w3.org/2000/svg">
	<foreignObject width="100%" height="100%">
		<div xmlns="http://www.w3.org/1999/xhtml">
			<style>
        
        @keyframes scroll {
          0% {
            left: 400px;
          }
          3% {
            left: 0px;
          }
          30% {
            left: 0px;
          }
          36% {
            left: -800px;
          }
          64% {
            left: -800px;
          }
          68% {
            left: -1600;
          }
          97% {
            left: -1600px
          }
          100% {
            left: -2000px
          }
        }
        @keyframes name {
          0% {
          transform: translateX(0px);
          }
          8% {
          transform: translateX(7px);
          }
          12% {
          transform: translateX(0px);
          }
          100% {
          transform: translateX(0px);
          }
        }
        @keyframes desc{
          0% {
          transform: translateX(0px);
          }
          10% {
          transform: translateX(12px);
          }
          15% {
          transform: translateX(0px);
          }
          90% {
            transform: translateX(0px);
            }
          95% {
            transform: translateX(-20px);
            }
          100% {
          transform: translateX(0px);
          }
        }
        @keyframes screen-name {
          0% {
          transform: rotate(-3deg);
          }
          41% {
          transform: rotate(-3deg);
          }
          47% {
          transform: rotate(2deg);
          }
          49% {
          transform: rotate(-2deg);
          }
          50% {
          transform: rotate(0deg);
          }
          51% {
          transform: rotate(-2deg);
          }
          55% {
          transform: rotate(-3deg);
          }
          51% {
          transform: rotate(2deg);
          }
          100% {
          transform: rotate(-3deg);
          }
        }
        ul.followers {
        margin: 0;
        padding: 0 2rem;
          position: absolute;
          list-style-type: none;
          display: flex;
          <!-- margin-top: 100px; -->
          justify-content: space-around;
          width: 2400px;
          animation: scroll 6s ease-out infinite;
        }
        ul.followers li {
        margin: 0;
          width: 854px;
          padding: 0 8rem;
        }
        ul.followers a {
          text-decoration: none;
          color: rgba(255, 255, 255, 0.83);
        }
        .name {
          display: inline-block;
          animation: name 2s infinite linear;
        }
        ul.followers h2 {
          padding: 0;
          margin: 0;
          font-family:Verdana, Geneva, Tahoma, sans-serif
        }
        ul.followers p {
          margin-left: 4rem;
          padding-left: 6px;
          animation: desc 2s infinite linear;
          border-left: 8px solid rgba(255, 255, 255, 0.308);
          border-left: 8px solid #FF66C4;
          border-left: 8px solid #FFD558;
        }
        .container {
          background: #18222E;
          height: 100%;
          width: 100%;
          height: 120px;
          width: 834px;
          color: rgba(255, 255, 255, 0.77);
          border: 5px solid transparent;
          border-image: linear-gradient(to bottom right, #b827fc 0%, #2c90fc 25%, #b8fd33 50%, #fec837 75%, #fd1892 100%);
          border-image: linear-gradient(to bottom right, #FF66C4 0%, #8C52FF 100%);
          border-image-slice: 1;
        }
        .screen-name {
          color: #FFD558;
          font-size: 1.2rem;
          padding-left: 1rem;
          display: inline-block;
          transform: rotate(-3deg);
          animation: screen-name 2s infinite linear;
        }
			</style>
			<div class="container">
        <ul class='followers'>
          <li>

            <h2>
            <a href='https://twitter.com/benjaminwardcom'>
                <span class='name'>Benjamin Wardr</span><span class='screen-name'><span class='screen-name'>@benjaminwardcom</span>
            </a>
            </h2>

            <p>
            software engineer, avid reader and writer, Star Wars fanatic, learning enthusiast
            </p>

          </li>
          <li>

            <h2>
            <a href='https://twitter.com/tucker_dev'>
                <span class='name'>James Tuckerr</span><span class='screen-name'><span class='screen-name'></span>@tucker_dev</span>
            </a>
            </h2>

            <p>
            software engineer at @soonastudios. career switcher. vue + rails. tweeting about tech, books, startups, and big ideas. writing @ https://t.co/SPyap1XFWD. he/him
            </p>

          </li>
          <li>
            <!-- <a href='https://twitter.com/BenGuthmiller'>
              <img style="border-radius:50%" align="left" src='https://pbs.twimg.com/profile_images/1284966756906409984/MR0a9hi2_normal.jpg' />
            </a> -->

            <h2>
            <a href='https://twitter.com/BenGuthmiller'>
                <span class='name'>Ben Guthmiller</span><span class='screen-name'>@BenGuthmiller</span>
            </a>
            </h2>

            <p>
            Data and Analytics Leader @IBM | Minnesota State Alum | #Technologist | #Investor | Tweets are my own opinions
            </p>

          </li>
        </ul>
			</div>
		</div>
	</foreignObject>
</svg> 
