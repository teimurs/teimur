HTML 

   div id="prozor" class="prozor">
            <div class="contact-form" style="background-image: url('https://images.jifo.co/28135055_1527509038810.jpg');"></div>

            <div class="txtb">
                <label>Full Name :</label>
                <input type="text" name="" value="" placeholder="Enter Your Name">
            </div>

            <div class="txtb">
                <label>Email :</label>
                <input type="email" name="" value="" placeholder="Enter Your Email">
            </div>

            <div class="txtb">
                <label>Phone Number :</label>
                <input type="text" name="" value="" placeholder="Enter Your Phone Number">
            </div>

            <div class="txtb">
                <label>Message :</label>
                <textarea></textarea>
            </div>
            <div class="btn btn-dark btn-block" id="send">Send</div>
        </div>



BUTTON CONTACT html isto


 button class="button" id="button1" onclick="prvi()">Contact</button>

 button class="button" id="button2" onclick="drugi()">Contact</button>

  button class="button" id="button3" onclick="treci()">Contact</button>


CSS 

.prozor {
    display: none;
    width: 85%;
    max-width: 600px;
    background-image: url('https://images.jifo.co/28135055_1527509038810.jpg');
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    padding: 30px 40px;
    box-sizing: border-box;
    border-radius: 8px;
    text-align: center;
    box-shadow: 0 0 20px #000000b3;
    font-family: "Montserrat", sans-serif;
    font-weight: 800;
    background-repeat: no-repeat;
    background-attachment: fixed;
    background-size: 100% 100%;
    width: 50%;
}

JS

('button3').addEventListener('click', treci);




function buttonClick() {


}

function prvi() {
    document.getElementById('button1').addEventListener('click', function() {


    });
    var x = document.getElementById('prozor');
    if (x.style.display === 'none') {
        x.style.display = 'block';
    } else {
        x.style.display = 'none';
    }

}

function drugi() {

    document.getElementById('button2').addEventListener('click', function() {

    });
    var x = document.getElementById('prozor');
    if (x.style.display === 'none') {
        x.style.display = 'block';
    } else {
        x.style.display = 'none';
    }



}

function treci() {

    document.getElementById('button3').addEventListener('click', function() {


    });
    var x = document.getElementById('prozor');
    if (x.style.display === 'none') {
        x.style.display = 'block';
    } else {
        x.style.display = 'none';
    }


};
