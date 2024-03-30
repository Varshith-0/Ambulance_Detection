<h1 class="major">Ambulance Detection</h1>
                  									<h3>Problem Statement</h3>
									<blockquote>Traffic congestion poses a significant challenge to emergency response efforts. Ambulances can become trapped in gridlock, leading to delays that can have life-or-death consequences. Existing traffic management systems often lack the capability to effectively prioritize emergency vehicles.</blockquote>
																		<h3>Proposed Solution</h3>
									<blockquote>This project offers a machine learning-based solution to address this critical challenge. By implementing a real-time ambulance detection system using YOLOv8, this project aims to:
          <li>Enhance emergency response efficiency by reducing ambulance travel times.</li>
<li>Potentially improve patient outcomes by allowing for faster medical intervention.</li>
<li>Streamline traffic management by dynamically adapting signal timing based on real-time traffic conditions and ambulance presence.</li>
         </blockquote>
         
## Key Features
<blockquote>
Here's a breakdown of the key features of this ambulance detector project:

* **Model Type:** YOLOv8n (lightweight and efficient)
* **Dataset:**
    * Source: Roboflow 
    * Image Distribution:
        * 21% Indian ambulances
        * 79% ambulances from other countries
    * Split:
        * Train: 536 images
        * Validation: 94 images
        * Test: 75 images
* **Model Performance:**
    * Training epochs: 200
    * Training time: 0.837 hours
    * Model size: ~6.3 MB (optimized)
    * Validation Results (on best.pt weight file):
        * mAP50: 0.941
        * mAP50-95: 0.736
        * Inference speed: 2.5ms per image
</blockquote>
<h3>Potential Applications</h3>
									<blockquote>
          <li>Intelligent traffic management systems</li>
<li>Emergency response coordination</li>
<li>Ambulance location tracking (in conjunction with GPS)</li>
         </blockquote>

									

