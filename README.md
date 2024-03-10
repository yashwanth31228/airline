
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>AeroList &mdash; Find Routes.</title>
    <link href="assets/css/bootstrap.min.css" rel="stylesheet">
    <link href="assets/css/font-awesome.css" rel="stylesheet">
    <!--    <link href="assets/css/style.css" rel="stylesheet">
-->
    <script src="https://code.jquery.com/jquery-3.6.0.min.js" integrity="sha256-/xUj+3OJU5yExlq6GSYGSHk7tPXikynS7ogEvDej/m4=" crossorigin="anonymous"></script>


    <script src="assets/js/data.js"></script>
    <script src="assets/js/data1.js"></script>
    <script src="assets/js/data2.js"></script>
</head>

<body>
    <section>
        <nav class="navbar navbar-light bg-light p-2 ">
            <a class="navbar-brand">
                <h2>AeroList <i class="fa fa-plane"></i></h2>
            </a>

        </nav>

    </section>
    <section class="fill">
        <div class="container my-5 p-3">

            <div class="">
                <h2>Find connecting routes, save money</h2>
                <p>Airlines do operate by source airports and destinations, but a larger unknown term is <strong>Sector</strong>, used to denote a flight route, connecting two or more airports, or simply, a <em>via route</em>
                    <br> We at Aerolist, used some magic (eh, just Data Analytics) to find you them, so your next trip can be planned easily and you can save some money
                </p>
                <p class="lead">Currently available for Indian Airports only.</p>
            </div>
            <hr>

            <form style="height: 50vh;">
                <div class="row">
                    <div class="form-group col-md-6 mb-3">
                        <select class="form-select" id="source" name="source">
                            <option>--Select Source Airport----</option>
                            <option value='AGR'>Agra</option>
                            <option value='AGX'>Agatti</option>
                            <option value='AJL'>Aizawl</option>
                            <option value='AMD'>Ahmedabad</option>
                            <option value='ATQ'>Amritsar</option>
                            <option value='BBI'>Bhubaneswar</option>
                            <option value='BDQ'>Vadodara</option>
                            <option value='BEK'>Bareilly</option>
                            <option value='BHO'>Bhopal</option>
                            <option value='BHU'>Bhavnagar</option>
                            <option value='BKB'>Bikaner</option>
                            <option value='BLR'>Bengaluru</option>
                            <option value='BOM'>Mumbai</option>
                            <option value='CCJ'>Calicut</option>
                            <option value='CCU'>Kolkata</option>
                            <option value='CJB'>Coimbatore</option>
                            <option value='CNN'>Kannur</option>
                            <option value='COK'>Kochi</option>
                            <option value='DBR'>Darbhanga</option>
                            <option value='DED'>Dehradun</option>
                            <option value='DEL'>New Delhi</option>
                            <option value='DHM'>Dharamshala</option>
                            <option value='DIB'>Dibrugarh</option>
                            <option value='DMU'>Dimapur</option>
                            <option value='GAU'>Guwahati</option>
                            <option value='GAY'>Gaya</option>
                            <option value='GBI'>Kalaburagi</option>
                            <option value='GOI'>Goa</option>
                            <option value='GOP'>Gorakhpur</option>
                            <option value='GWL'>Gwalior</option>
                            <option value='HBX'>Hubballi</option>
                            <option value='HYD'>Hyderabad</option>
                            <option value='IDR'>Indore</option>
                            <option value='IMF'>Imphal</option>
                            <option value='ISK'>Nashik</option>
                            <option value='IXA'>Agartala</option>
                            <option value='IXB'>Bagdogra</option>
                            <option value='IXC'>Chandigarh</option>
                            <option value='IXD'>Allahabad</option>
                            <option value='IXE'>Mangaluru</option>
                            <option value='IXG'>Belagavi</option>
                            <option value='IXI'>Lilabari</option>
                            <option value='IXJ'>Jammu</option>
                            <option value='IXL'>Leh</option>
                            <option value='IXM'>Madurai</option>
                            <option value='IXP'>Pathankot</option>
                            <option value='IXR'>Ranchi</option>
                            <option value='IXS'>Silchar</option>
                            <option value='IXT'>Pasighat</option>
                            <option value='IXU'>Aurangabad</option>
                            <option value='IXY'>Kandla</option>
                            <option value='IXZ'>Port Blair</option>
                            <option value='JAI'>Jaipur</option>
                            <option value='JDH'>Jodhpur</option>
                            <option value='JGA'>Jamnagar</option>
                            <option value='JGB'>Jagdalpur</option>
                            <option value='JLR'>Jabalpur</option>
                            <option value='JRG'>Jharsuguda</option>
                            <option value='JRH'>Jorhat</option>
                            <option value='JSA'>Jaiselmer</option>
                            <option value='KLH'>Kolhapur</option>
                            <option value='KNU'>Kanpur</option>
                            <option value='KQH'>Ajmer</option>
                            <option value='KUU'>Kullu</option>
                            <option value='LKO'>Lucknow</option>
                            <option value='LUH'>Ludhiana</option>
                            <option value='MAA'>Chennai</option>
                            <option value='MYQ'>Mysore</option>
                            <option value='NAG'>Nagpur</option>
                            <option value='NDC'>Nanded</option>
                            <option value='PAB'>Bilaspur</option>
                            <option value='PAT'>Patna</option>
                            <option value='PBD'>Porbandar</option>
                            <option value='PGH'>Pantnagar</option>
                            <option value='PNQ'>Pune</option>
                            <option value='PNY'>Pondicherry</option>
                            <option value='PYG'>PAKYONG</option>
                            <option value='RAJ'>Rajkot</option>
                            <option value='RDP'>Durgapur</option>
                            <option value='RJA'>Rajahmundry</option>
                            <option value='RPR'>Raipur</option>
                            <option value='SAG'>Shirdi</option>
                            <option value='STV'>Surat</option>
                            <option value='SXR'>Srinagar</option>
                            <option value='TCR'>Tuticorin</option>
                            <option value='TEZ'>Tezpur</option>
                            <option value='TIR'>Tirupati</option>
                            <option value='TRV'>Thiruvananthapuram</option>
                            <option value='TRZ'>Tiruchirappally</option>
                            <option value='UDR'>Udaipur</option>
                            <option value='VGA'>Vijayawada</option>
                            <option value='VNS'>Varanasi</option>
                            <option value='VTZ'>Visakhapatnam</option>



                        </select>
                    </div>

                    <div class="col-md-6 mb-3">
                        <select class="form-select" id="dest" name="dest">
                            <option>--Select Source Airport----</option>
                            <option value='AGR'>Agra</option>
                            <option value='AGX'>Agatti</option>
                            <option value='AJL'>Aizawl</option>
                            <option value='AMD'>Ahmedabad</option>
                            <option value='ATQ'>Amritsar</option>
                            <option value='BBI'>Bhubaneswar</option>
                            <option value='BDQ'>Vadodara</option>
                            <option value='BEK'>Bareilly</option>
                            <option value='BHO'>Bhopal</option>
                            <option value='BHU'>Bhavnagar</option>
                            <option value='BKB'>Bikaner</option>
                            <option value='BLR'>Bengaluru</option>
                            <option value='BOM'>Mumbai</option>
                            <option value='CCJ'>Calicut</option>
                            <option value='CCU'>Kolkata</option>
                            <option value='CJB'>Coimbatore</option>
                            <option value='CNN'>Kannur</option>
                            <option value='COK'>Kochi</option>
                            <option value='DBR'>Darbhanga</option>
                            <option value='DED'>Dehradun</option>
                            <option value='DEL'>New Delhi</option>
                            <option value='DHM'>Dharamshala</option>
                            <option value='DIB'>Dibrugarh</option>
                            <option value='DMU'>Dimapur</option>
                            <option value='GAU'>Guwahati</option>
                            <option value='GAY'>Gaya</option>
                            <option value='GBI'>Kalaburagi</option>
                            <option value='GOI'>Goa</option>
                            <option value='GOP'>Gorakhpur</option>
                            <option value='GWL'>Gwalior</option>
                            <option value='HBX'>Hubballi</option>
                            <option value='HYD'>Hyderabad</option>
                            <option value='IDR'>Indore</option>
                            <option value='IMF'>Imphal</option>
                            <option value='ISK'>Nashik</option>
                            <option value='IXA'>Agartala</option>
                            <option value='IXB'>Bagdogra</option>
                            <option value='IXC'>Chandigarh</option>
                            <option value='IXD'>Allahabad</option>
                            <option value='IXE'>Mangaluru</option>
                            <option value='IXG'>Belagavi</option>
                            <option value='IXI'>Lilabari</option>
                            <option value='IXJ'>Jammu</option>
                            <option value='IXL'>Leh</option>
                            <option value='IXM'>Madurai</option>
                            <option value='IXP'>Pathankot</option>
                            <option value='IXR'>Ranchi</option>
                            <option value='IXS'>Silchar</option>
                            <option value='IXT'>Pasighat</option>
                            <option value='IXU'>Aurangabad</option>
                            <option value='IXY'>Kandla</option>
                            <option value='IXZ'>Port Blair</option>
                            <option value='JAI'>Jaipur</option>
                            <option value='JDH'>Jodhpur</option>
                            <option value='JGA'>Jamnagar</option>
                            <option value='JGB'>Jagdalpur</option>
                            <option value='JLR'>Jabalpur</option>
                            <option value='JRG'>Jharsuguda</option>
                            <option value='JRH'>Jorhat</option>
                            <option value='JSA'>Jaiselmer</option>
                            <option value='KLH'>Kolhapur</option>
                            <option value='KNU'>Kanpur</option>
                            <option value='KQH'>Ajmer</option>
                            <option value='KUU'>Kullu</option>
                            <option value='LKO'>Lucknow</option>
                            <option value='LUH'>Ludhiana</option>
                            <option value='MAA'>Chennai</option>
                            <option value='MYQ'>Mysore</option>
                            <option value='NAG'>Nagpur</option>
                            <option value='NDC'>Nanded</option>
                            <option value='PAB'>Bilaspur</option>
                            <option value='PAT'>Patna</option>
                            <option value='PBD'>Porbandar</option>
                            <option value='PGH'>Pantnagar</option>
                            <option value='PNQ'>Pune</option>
                            <option value='PNY'>Pondicherry</option>
                            <option value='PYG'>PAKYONG</option>
                            <option value='RAJ'>Rajkot</option>
                            <option value='RDP'>Durgapur</option>
                            <option value='RJA'>Rajahmundry</option>
                            <option value='RPR'>Raipur</option>
                            <option value='SAG'>Shirdi</option>
                            <option value='STV'>Surat</option>
                            <option value='SXR'>Srinagar</option>
                            <option value='TCR'>Tuticorin</option>
                            <option value='TEZ'>Tezpur</option>
                            <option value='TIR'>Tirupati</option>
                            <option value='TRV'>Thiruvananthapuram</option>
                            <option value='TRZ'>Tiruchirappally</option>
                            <option value='UDR'>Udaipur</option>
                            <option value='VGA'>Vijayawada</option>
                            <option value='VNS'>Varanasi</option>
                            <option value='VTZ'>Visakhapatnam</option>



                        </select>
                    </div>
                </div>
                <div class="col-md-12 mb-3">
                    <button type="button" class="btn btn-lg btn-primary btn-block" onclick="initvar()" data-toggle="modal" data-target="#exampleModal">
                        Find
                    </button>
                </div>


            </form>
            <!-- Button trigger modal -->


            <!-- Modal -->
            <div class="modal fade" id="exampleModal" tabindex="-1" role="dialog" aria-labelledby="exampleModalLabel" aria-hidden="true">
                <div class="modal-dialog modal-xl" role="document" style="max-width: 80%;">
                    <div class="modal-content">
                        <div class="modal-header bg-blue">
                            <h5 class="modal-title" id="exampleModalLabel">Search Result</h5>
                            <button type="button" class="close" data-dismiss="modal" aria-label="Close">
                                <span aria-hidden="true" class="text-white">&times;</span>
                            </button>
                        </div>
                        <div class="modal-body">

                            <h4 class="card-title text-dark">
                                <span id="op_source"></span> &mdash; <span id="op_dest"></span>
                            </h4>

                            <hr>
                            <div class="alert alert-info" id="msg"></div>
                            <table class='table table-hover'>
                                <thead>
                                    <tr>
                                        <th scope='col'>Carriers</th>
                                        <th scope='col'>Route</th>
                                        <th scope='col'>Avg Cost* </th>
                                    </tr>
                                </thead>
                            </table>

                            <!--
<div class="card">
                                <div class="card-body py-3">
                                    <div class="row">
                                        <span class="col text-left">
                                            6E, AI
                                        </span>
                                        <span class="col text-center">
                                            <p> ABC&mdash;XYZ</p>
                                        </span>
                                        <span class="col text-right">
                                            ₹ 0000
                                        </span>
                                    </div>
                                </div>
                            </div>
                            -->


                            <div id="result"></div>
                            *<small>Average Cost is the Raw fare calculated by flight distance, fuel prices and other constant fees. Dynamic prices are not applicable, please check with service-provider or airlines for accurate pricing.</small>
                        </div>

                    </div>
                </div>
            </div>
        </div>
    </section>
    <footer class="bg-dark text-white text-center text-lg-start">
        <!-- Copyright -->
        <div class="text-center p-3 text-white ">
            <h5>All Rights Reserved © 2021</h5>
            <p class="lead text-muted ">
                Aerolist &mdash; <a href="https://jedetin.github.io ">jedetin.github.io</a></p>
        </div>
        <!-- Copyright -->
    </footer>
</body>
<script src="assets/js/bootstrap.js"></script>
<script src="assets/js/script-ind.js"></script>

</html>
