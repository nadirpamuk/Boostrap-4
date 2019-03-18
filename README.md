# Boostrap-4


When I click to the image, the cycling starts from the end image. I click left and travel to the first image which is supposed to be the opposite.

</-- HTML PART -- >

              <div class="col-md-4">
                  <a href="images/SC/SC-1.jpg" data-lightbox="SCTM" data-title="Science Center and Technology Museum">
                  <a href="images/SC/SC-Concept.jpg" data-lightbox="SCTM" data-title="Analysis">
                  <a href="images/SC/SC-Groundfloor.jpg" data-lightbox="SCTM" data-title="Floor Plans">
                  <a href="images/SC/SC-Floorplans.jpg" data-lightbox="SCTM" data-title="Floor Plans">
                  <a href="images/SC/interior.jpg" data-lightbox="SCTM" data-title="Ground Floor Interior View">
                  <a href="images/SC/SC-Sections2.jpg" data-lightbox="SCTM" data-title="Section Plan">
                  <a href="images/SC/SC-Sections.jpg" data-lightbox="SCTM" data-title="Section Plans">
                  <a href="images/SC/Landscape.jpg" data-lightbox="SCTM" data-title="Landscape View">
                    <div class="imageContainer">
                        <img src="images/SC/SC_cover.jpg" class="img-fluid">
                        <div class="imageOverlay">
                            <div class="imageText">
                                <h4>Science Center and Technology Museum</h4>
                                <h5>Project Location:</h5>
                                <p>Golden Horn/Istanbul</p>
                                <h5>Project Type:</h5>
                                <p>Museum</p>
                                <h5>Project Date:</h5>
                                <p>2017</p>
                                <h5>Project Area:</h5>
                                <p>17.000 sqm</p>
                            </div>
                        </div>
                    </div>
                 </a>
                 </a>
                 </a>
                 </a>
                 </a>
                 </a>
                 </a>
                 </a>
            </div>
            <div class="col-md-4">
                
 </-- CSS PART -- >
         
            .imageContainer {
                position: relative;
                cursor: pointer;
                top: 17px;
            }

            .imageOverlay {
                position: absolute;
                top: 0;
                bottom: 0;
                right: 0;
                left: 0;
                height: 100%;
                width: 100%;
                background-color: #cd1414;
                opacity: 0;
                transition: .5s ease;
            }

            .imageContainer:hover .imageOverlay {
                opacity: .9;
            }

            .imageText {
                color: white;
                position: absolute;
                top: 50%;
                left: 50%;
                transform: translate(-50%, -50%);
                text-align: center;
                font-family: 'Slabo 27px', serif;
                line-height: 2px;
            }
