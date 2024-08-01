---
nav_title: Message Credits - Sigma
permalink: "/message_credits_sigma_pow2/"
hidden: true
noindex: true
hide_toc: true
---

# Message Credits - Sigma (Confidential)

> Message Credits is Braze’s cross-channel packaging structure for our native SMS, MMS, and WhatsApp offerings. We use Message Credits to provide a flexible and transparent experience when taking advantage of Braze messaging channels. You may use the allotment of credits purchased across any of the channels presented in the table on this page.

{% alert note %}
Different channels will have different units of measure in reporting.<br><br>
<b>WhatsApp:</b> Conversations<br>
<b>SMS:</b> Segments<br>
<b>MMS:</b> Segments<br><br>
In other words, credits used for WhatsApp messages will be calculated on conversation initiations, and credits used for both SMS and MMS messages will be calculated on segments sent.
<br><br>
Lastly, carrier fees are billed separately (in arrears) and are not considered as part of this Message Credits SKU.
{% endalert %}

## Definitions

Column definitions are as follows:

|---------|-------------------------------------------------|
| **Channel Credit Ratio** | Baseline credit amount for each channel |
| **Destination** | Specific final region, country, or type of message being sent through the Braze platform |
| **Multiplier** | Scaler to the Channel Credit Ratio, depending on pricing of the specific destination |
| **Credits Used with 1 Send** | Exact number of Message Credits used to send one message<br> (credits per message = channel credit ratio x destination multiplier) |
{: .reset-td-br-1 .reset-td-br-2}


## Credit ratio table for Message Credits - Sigma

{% details Click to expand %}
<table>
    <colgroup>
        <col span="4" style="background-color:background-color:#FFFFFF;">
        <col style="background-color:#f0f0f5">
    </colgroup>
    <tr>
        <th><b>Channel</b></th>
        <th><b>Channel Credit Ratio</b></th>
        <th><b>Destination</b></th>
        <th><b>Multiplier</b></th>
        <th class="credits-column"><b>Credits Used with 1 Send</b></th>
    </tr>
    <tbody><tr>
        <td>SMS - US / CA</td>
        <td>1</td>
        <td>United States</td>
        <td>1.00</td>
        <td>1.00</td>
    </tr>
    <tr>
        <td>SMS - US / CA</td>
        <td>1</td>
        <td>United States Toll Free</td>
        <td>1.50</td>
        <td>1.50</td>
    </tr>
    <tr>
        <td>SMS - US / CA</td>
        <td>1</td>
        <td>Canada</td>
        <td>1.00</td>
        <td>1.00</td>
    </tr>
    <tr>
        <td>SMS - US / CA</td>
        <td>1</td>
        <td>Canada Toll Free</td>
        <td>1.30</td>
        <td>1.30</td>
    </tr>
    <tr>
        <td>MMS - US / CA</td>
        <td>3</td>
        <td>United States</td>
        <td>1.00</td>
        <td>3.00</td>
    </tr>
    <tr>
        <td>MMS - US / CA</td>
        <td>3</td>
        <td>United States Toll Free</td>
        <td>2.00</td>
        <td>6.00</td>
    </tr>
    <tr>
        <td>MMS - US / CA</td>
        <td>3</td>
        <td>Canada Long Code</td>
        <td>1.50</td>
        <td>4.50</td>
    </tr>
    <tr>
        <td>MMS - US / CA</td>
        <td>3</td>
        <td>Canada Short Code</td>
        <td>4.00</td>
        <td>12.00</td>
    </tr>
    <tr>
        <td>MMS - US / CA</td>
        <td>3</td>
        <td>Canada Toll Free</td>
        <td>1.30</td>
        <td>3.90</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Abkhazia</td>
        <td>0.62</td>
        <td>4.65</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Afghanistan</td>
        <td>9.47</td>
        <td>71.03</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Albania</td>
        <td>2.29</td>
        <td>17.18</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Algeria</td>
        <td>5.23</td>
        <td>39.23</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>American Samoa</td>
        <td>4.74</td>
        <td>35.55</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Andorra</td>
        <td>3.32</td>
        <td>24.90</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Angola</td>
        <td>2.24</td>
        <td>16.80</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Anguilla</td>
        <td>3.33</td>
        <td>24.98</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Antigua and Barbuda</td>
        <td>2.47</td>
        <td>18.53</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Argentina</td>
        <td>1.02</td>
        <td>7.65</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Armenia</td>
        <td>3.49</td>
        <td>26.18</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Aruba</td>
        <td>2.61</td>
        <td>19.58</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Australia SMS</td>
        <td>0.36</td>
        <td>2.70</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Australia MMS</td>
        <td>3.10</td>
        <td>23.25</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Austria</td>
        <td>1.77</td>
        <td>13.28</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Azerbaijan</td>
        <td>9.77</td>
        <td>73.28</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Bahamas</td>
        <td>1.23</td>
        <td>9.23</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Bahrain</td>
        <td>0.92</td>
        <td>6.90</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Bangladesh</td>
        <td>5.81</td>
        <td>43.58</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Barbados</td>
        <td>3.09</td>
        <td>23.18</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Belarus</td>
        <td>6.35</td>
        <td>47.63</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Belgium</td>
        <td>2.40</td>
        <td>18.00</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Belize</td>
        <td>6.90</td>
        <td>51.75</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Benin</td>
        <td>3.64</td>
        <td>27.30</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Bermuda</td>
        <td>2.99</td>
        <td>22.43</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Bhutan</td>
        <td>10.10</td>
        <td>75.75</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Bolivia</td>
        <td>3.66</td>
        <td>27.45</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Bosnia and Herzegovina</td>
        <td>2.12</td>
        <td>15.90</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Botswana</td>
        <td>2.52</td>
        <td>18.90</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Brazil</td>
        <td>0.25</td>
        <td>1.88</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Brunei</td>
        <td>0.50</td>
        <td>3.75</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Bulgaria</td>
        <td>2.70</td>
        <td>20.25</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Burkina Faso</td>
        <td>3.35</td>
        <td>25.13</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Burundi</td>
        <td>9.47</td>
        <td>71.03</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Cambodia</td>
        <td>4.30</td>
        <td>32.25</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Cameroon</td>
        <td>3.49</td>
        <td>26.18</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Cape Verde</td>
        <td>3.66</td>
        <td>27.45</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Caribbean Netherlands</td>
        <td>2.17</td>
        <td>16.28</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Cayman Islands</td>
        <td>3.37</td>
        <td>25.28</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Central African Republic</td>
        <td>3.07</td>
        <td>23.03</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Chad</td>
        <td>7.30</td>
        <td>54.75</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Chile</td>
        <td>1.64</td>
        <td>12.30</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>China</td>
        <td>0.64</td>
        <td>4.80</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Colombia</td>
        <td>0.02</td>
        <td>0.15</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Comoros</td>
        <td>6.19</td>
        <td>46.43</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Congo</td>
        <td>5.04</td>
        <td>37.80</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Cook Islands</td>
        <td>3.52</td>
        <td>26.40</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Costa Rica</td>
        <td>1.06</td>
        <td>7.95</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Croatia</td>
        <td>2.31</td>
        <td>17.33</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Cuba</td>
        <td>2.12</td>
        <td>15.90</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Curacao</td>
        <td>0.99</td>
        <td>7.43</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Cyprus</td>
        <td>2.18</td>
        <td>16.35</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Czech Republic</td>
        <td>1.01</td>
        <td>7.58</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Denmark</td>
        <td>1.01</td>
        <td>7.58</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Djibouti</td>
        <td>4.09</td>
        <td>30.68</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Dominica</td>
        <td>3.79</td>
        <td>28.43</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Dominican Republic</td>
        <td>1.29</td>
        <td>9.68</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>DR Congo</td>
        <td>5.77</td>
        <td>43.28</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Ecuador</td>
        <td>2.76</td>
        <td>20.70</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Egypt</td>
        <td>2.43</td>
        <td>18.23</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>El Salvador</td>
        <td>2.45</td>
        <td>18.38</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Equatorial Guinea</td>
        <td>4.36</td>
        <td>32.70</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Eritrea</td>
        <td>2.48</td>
        <td>18.60</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Estonia</td>
        <td>2.41</td>
        <td>18.08</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Eswatini</td>
        <td>0.58</td>
        <td>4.35</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Ethiopia</td>
        <td>8.63</td>
        <td>64.73</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Falkland Islands</td>
        <td>3.43</td>
        <td>25.73</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Faroe Islands</td>
        <td>1.70</td>
        <td>12.75</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Fiji</td>
        <td>4.16</td>
        <td>31.20</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Finland</td>
        <td>1.46</td>
        <td>10.95</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>France</td>
        <td>0.98</td>
        <td>7.35</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>French Guiana</td>
        <td>4.64</td>
        <td>34.80</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>French Polynesia</td>
        <td>4.53</td>
        <td>33.98</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Gabon</td>
        <td>6.64</td>
        <td>49.80</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Gambia</td>
        <td>4.18</td>
        <td>31.35</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Georgia</td>
        <td>2.63</td>
        <td>19.73</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Germany</td>
        <td>1.88</td>
        <td>14.10</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Ghana</td>
        <td>2.26</td>
        <td>16.95</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Gibraltar</td>
        <td>2.75</td>
        <td>20.63</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Greece</td>
        <td>0.99</td>
        <td>7.43</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Greenland</td>
        <td>1.03</td>
        <td>7.73</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Grenada</td>
        <td>4.09</td>
        <td>30.68</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Guadeloupe</td>
        <td>3.40</td>
        <td>25.50</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Guam</td>
        <td>1.73</td>
        <td>12.98</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Guatemala</td>
        <td>3.20</td>
        <td>24.00</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Guernsey</td>
        <td>0.87</td>
        <td>6.53</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Guinea</td>
        <td>3.82</td>
        <td>28.65</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Guinea-Bissau</td>
        <td>3.97</td>
        <td>29.78</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Guyana</td>
        <td>4.50</td>
        <td>33.75</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Haiti</td>
        <td>5.94</td>
        <td>44.55</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Honduras</td>
        <td>2.13</td>
        <td>15.98</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Hong Kong</td>
        <td>1.35</td>
        <td>10.13</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Hungary</td>
        <td>1.91</td>
        <td>14.33</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Iceland</td>
        <td>1.75</td>
        <td>13.13</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>India</td>
        <td>1.00</td>
        <td>7.50</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Indonesia</td>
        <td>6.63</td>
        <td>49.73</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Iran</td>
        <td>6.25</td>
        <td>46.88</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Iraq</td>
        <td>4.79</td>
        <td>35.93</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Ireland</td>
        <td>1.31</td>
        <td>9.83</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Isle of Man</td>
        <td>0.81</td>
        <td>6.08</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Israel</td>
        <td>3.74</td>
        <td>28.05</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Italy</td>
        <td>0.78</td>
        <td>5.85</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Ivory Coast</td>
        <td>2.48</td>
        <td>18.60</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Jamaica</td>
        <td>3.05</td>
        <td>22.88</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Japan</td>
        <td>1.02</td>
        <td>7.65</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Jersey</td>
        <td>0.70</td>
        <td>5.25</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Jordan</td>
        <td>5.56</td>
        <td>41.70</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Kazakhstan</td>
        <td>5.52</td>
        <td>41.40</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Kenya</td>
        <td>2.62</td>
        <td>19.65</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Kiribati</td>
        <td>3.67</td>
        <td>27.53</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Korea Republic of</td>
        <td>0.69</td>
        <td>5.18</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Kosovo</td>
        <td>0.97</td>
        <td>7.28</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Kuwait</td>
        <td>3.34</td>
        <td>25.05</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Kyrgyzstan</td>
        <td>6.12</td>
        <td>45.90</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Laos PDR</td>
        <td>1.54</td>
        <td>11.55</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Latvia</td>
        <td>1.80</td>
        <td>13.50</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Lebanon</td>
        <td>3.07</td>
        <td>23.03</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Lesotho</td>
        <td>5.14</td>
        <td>38.55</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Liberia</td>
        <td>3.47</td>
        <td>26.03</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Libya</td>
        <td>8.17</td>
        <td>61.28</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Liechtenstein</td>
        <td>0.84</td>
        <td>6.30</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Lithuania</td>
        <td>1.37</td>
        <td>10.28</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Luxembourg</td>
        <td>1.86</td>
        <td>13.95</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Macao</td>
        <td>1.49</td>
        <td>11.18</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Macedonia</td>
        <td>1.88</td>
        <td>14.10</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Madagascar</td>
        <td>9.40</td>
        <td>70.50</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Malawi</td>
        <td>5.72</td>
        <td>42.90</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Malaysia</td>
        <td>1.47</td>
        <td>11.03</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Maldives</td>
        <td>1.80</td>
        <td>13.50</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Mali</td>
        <td>3.97</td>
        <td>29.78</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Malta</td>
        <td>1.64</td>
        <td>12.30</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Marshall Islands</td>
        <td>4.00</td>
        <td>30.00</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Martinique</td>
        <td>3.33</td>
        <td>24.98</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Mauritania</td>
        <td>6.51</td>
        <td>48.83</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Mauritius</td>
        <td>4.02</td>
        <td>30.15</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Mayotte</td>
        <td>2.33</td>
        <td>17.48</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Mexico</td>
        <td>0.27</td>
        <td>2.03</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Micronesia</td>
        <td>1.85</td>
        <td>13.88</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Moldova</td>
        <td>1.59</td>
        <td>11.93</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Monaco</td>
        <td>4.68</td>
        <td>35.10</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Mongolia</td>
        <td>7.03</td>
        <td>52.73</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Montenegro</td>
        <td>2.87</td>
        <td>21.53</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Montserrat</td>
        <td>2.77</td>
        <td>20.78</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Morocco</td>
        <td>2.64</td>
        <td>19.80</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Mozambique</td>
        <td>2.76</td>
        <td>20.70</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Myanmar</td>
        <td>5.84</td>
        <td>43.80</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Namibia</td>
        <td>1.58</td>
        <td>11.85</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Nauru</td>
        <td>1.12</td>
        <td>8.40</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Nepal</td>
        <td>3.82</td>
        <td>28.65</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Netherlands</td>
        <td>1.65</td>
        <td>12.38</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>New Caledonia</td>
        <td>4.44</td>
        <td>33.30</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>New Zealand</td>
        <td>1.92</td>
        <td>14.40</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Nicaragua</td>
        <td>1.95</td>
        <td>14.63</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Niger</td>
        <td>7.49</td>
        <td>56.18</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Nigeria</td>
        <td>5.01</td>
        <td>37.58</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Niue</td>
        <td>4.86</td>
        <td>36.45</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Norfolk Island</td>
        <td>0.71</td>
        <td>5.33</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>North Macedonia</td>
        <td>0.34</td>
        <td>2.55</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Northern Cyprus</td>
        <td>0.20</td>
        <td>1.50</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Norway</td>
        <td>1.05</td>
        <td>7.88</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Oman</td>
        <td>3.60</td>
        <td>27.00</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Pakistan</td>
        <td>7.46</td>
        <td>55.95</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Palau</td>
        <td>2.52</td>
        <td>18.90</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Palestinian Territory</td>
        <td>7.68</td>
        <td>57.60</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Panama</td>
        <td>2.23</td>
        <td>16.73</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Papua New Guinea</td>
        <td>19.01</td>
        <td>142.58</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Paraguay</td>
        <td>1.84</td>
        <td>13.80</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Peru</td>
        <td>0.81</td>
        <td>6.08</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Philippines</td>
        <td>0.28</td>
        <td>2.10</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Poland</td>
        <td>0.52</td>
        <td>3.90</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Portugal</td>
        <td>0.60</td>
        <td>4.50</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Puerto Rico</td>
        <td>1.06</td>
        <td>7.95</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Qatar</td>
        <td>0.52</td>
        <td>3.90</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Reunion/Mayotte</td>
        <td>4.82</td>
        <td>36.15</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Romania</td>
        <td>1.06</td>
        <td>7.95</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Russia</td>
        <td>9.54</td>
        <td>71.55</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Rwanda</td>
        <td>4.66</td>
        <td>34.95</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Saint Kitts and Nevis</td>
        <td>0.92</td>
        <td>6.90</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Saint Lucia</td>
        <td>1.07</td>
        <td>8.03</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Saint Pierre and Miquelon</td>
        <td>2.31</td>
        <td>17.33</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Saint Vincent and The Grenadines</td>
        <td>1.06</td>
        <td>7.95</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Samoa</td>
        <td>4.68</td>
        <td>35.10</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>San Marino</td>
        <td>2.76</td>
        <td>20.70</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Sao Tome and Principe</td>
        <td>3.29</td>
        <td>24.68</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Saudi Arabia</td>
        <td>1.91</td>
        <td>14.33</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Senegal</td>
        <td>5.15</td>
        <td>38.63</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Serbia</td>
        <td>6.09</td>
        <td>45.68</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Seychelles</td>
        <td>0.94</td>
        <td>7.05</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Sierra Leone</td>
        <td>4.73</td>
        <td>35.48</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Singapore</td>
        <td>0.70</td>
        <td>5.25</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Sint Maarten</td>
        <td>0.16</td>
        <td>1.20</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Slovakia</td>
        <td>2.23</td>
        <td>16.73</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Slovenia</td>
        <td>3.76</td>
        <td>28.20</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Solomon Islands</td>
        <td>2.09</td>
        <td>15.68</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Somalia</td>
        <td>4.74</td>
        <td>35.55</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>South Africa</td>
        <td>0.32</td>
        <td>2.40</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>South Ossetia</td>
        <td>2.05</td>
        <td>15.38</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>South Sudan</td>
        <td>0.80</td>
        <td>6.00</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Spain</td>
        <td>0.80</td>
        <td>6.00</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Sri Lanka</td>
        <td>5.60</td>
        <td>42.00</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Sudan</td>
        <td>4.15</td>
        <td>31.13</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Suriname</td>
        <td>3.28</td>
        <td>24.60</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Swaziland</td>
        <td>2.32</td>
        <td>17.40</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Sweden</td>
        <td>0.86</td>
        <td>6.45</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Switzerland</td>
        <td>0.60</td>
        <td>4.50</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Syria</td>
        <td>7.86</td>
        <td>58.95</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Taiwan</td>
        <td>0.84</td>
        <td>6.30</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Tajikistan</td>
        <td>11.35</td>
        <td>85.13</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Tanzania</td>
        <td>5.38</td>
        <td>40.35</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Thailand</td>
        <td>0.36</td>
        <td>2.70</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Timor-Leste</td>
        <td>2.86</td>
        <td>21.45</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Togo</td>
        <td>3.84</td>
        <td>28.80</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Tonga</td>
        <td>3.14</td>
        <td>23.55</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Trinidad and Tobago</td>
        <td>3.02</td>
        <td>22.65</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Tunisia</td>
        <td>7.06</td>
        <td>52.95</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Turkey</td>
        <td>0.77</td>
        <td>5.78</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Turkmenistan</td>
        <td>5.04</td>
        <td>37.80</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Turks and Caicos Islands</td>
        <td>3.38</td>
        <td>25.35</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Tuvalu</td>
        <td>3.36</td>
        <td>25.20</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Uganda</td>
        <td>4.05</td>
        <td>30.38</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Ukraine</td>
        <td>2.86</td>
        <td>21.45</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>United Arab Emirates</td>
        <td>1.24</td>
        <td>9.30</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>United Kingdom</td>
        <td>0.65</td>
        <td>4.88</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Unknown</td>
        <td>3.92</td>
        <td>29.40</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Uruguay</td>
        <td>2.15</td>
        <td>16.13</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Uzbekistan</td>
        <td>6.88</td>
        <td>51.60</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Vanuatu</td>
        <td>4.18</td>
        <td>31.35</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Venezuela</td>
        <td>2.15</td>
        <td>16.13</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Vietnam</td>
        <td>3.05</td>
        <td>22.88</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Virgin Islands, British</td>
        <td>4.73</td>
        <td>35.48</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Virgin Islands, U.S.</td>
        <td>0.50</td>
        <td>3.75</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Wallis and Futuna</td>
        <td>2.77</td>
        <td>20.78</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Yemen</td>
        <td>6.03</td>
        <td>45.23</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Zambia</td>
        <td>6.76</td>
        <td>50.70</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Zimbabwe</td>
        <td>3.55</td>
        <td>26.63</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Argentina Authentication</td>
        <td>0.95</td>
        <td>7.13</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Argentina Marketing</td>
        <td>1.65</td>
        <td>12.38</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Argentina Service</td>
        <td>0.85</td>
        <td>6.38</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Argentina Utility</td>
        <td>1.10</td>
        <td>6.75</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Brazil Authentication</td>
        <td>0.85</td>
        <td>6.38</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Brazil Marketing</td>
        <td>1.65</td>
        <td>12.38</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Brazil Service</td>
        <td>0.80</td>
        <td>6.00</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Brazil Utility</td>
        <td>0.95</td>
        <td>1.58</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Chile Authentication</td>
        <td>1.40</td>
        <td>10.50</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Chile Marketing</td>
        <td>2.35</td>
        <td>17.63</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Chile Service</td>
        <td>1.20</td>
        <td>9.00</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Chile Utility</td>
        <td>1.55</td>
        <td>3.98</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Colombia Authentication</td>
        <td>0.20</td>
        <td>1.50</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Colombia Marketing</td>
        <td>0.35</td>
        <td>2.63</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Colombia Service</td>
        <td>0.15</td>
        <td>1.13</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Colombia Utility</td>
        <td>0.25</td>
        <td>0.08</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Egypt Authentication</td>
        <td>1.65</td>
        <td>12.38</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Egypt Marketing</td>
        <td>2.85</td>
        <td>21.38</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Egypt Service</td>
        <td>1.70</td>
        <td>12.75</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Egypt Utility</td>
        <td>1.80</td>
        <td>1.05</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>France Authentication</td>
        <td>1.85</td>
        <td>13.88</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>France Marketing</td>
        <td>3.80</td>
        <td>28.50</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>France Service</td>
        <td>2.30</td>
        <td>17.25</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>France Utility</td>
        <td>2.05</td>
        <td>6.00</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Germany Authentication</td>
        <td>2.05</td>
        <td>15.38</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Germany Marketing</td>
        <td>3.60</td>
        <td>27.00</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Germany Service</td>
        <td>2.15</td>
        <td>16.13</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Germany Utility</td>
        <td>2.25</td>
        <td>10.95</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>India Authentication</td>
        <td>0.04</td>
        <td>0.30</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>India Authentication - International</td>
        <td>0.74</td>
        <td>5.55</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>India Marketing</td>
        <td>0.25</td>
        <td>1.88</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>India Service</td>
        <td>0.10</td>
        <td>0.75</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>India Utility</td>
        <td>0.10</td>
        <td>0.30</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Indonesia Authentication</td>
        <td>0.80</td>
        <td>6.00</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Indonesia Authentication - International</td>
        <td>3.61</td>
        <td>27.08</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Indonesia Marketing</td>
        <td>1.10</td>
        <td>8.25</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Indonesia Service</td>
        <td>0.50</td>
        <td>3.75</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Indonesia Utility</td>
        <td>0.55</td>
        <td>4.13</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Israel Authentication</td>
        <td>0.45</td>
        <td>3.38</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Israel Marketing</td>
        <td>0.95</td>
        <td>7.13</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Israel Service</td>
        <td>0.50</td>
        <td>3.75</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Israel Utility</td>
        <td>0.50</td>
        <td>1.05</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Italy Authentication</td>
        <td>1.00</td>
        <td>7.50</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Italy Marketing</td>
        <td>1.85</td>
        <td>13.88</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Italy Service</td>
        <td>1.00</td>
        <td>7.50</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Italy Utility</td>
        <td>1.10</td>
        <td>6.00</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Malaysia Authentication</td>
        <td>0.50</td>
        <td>3.75</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Malaysia Marketing</td>
        <td>2.30</td>
        <td>17.25</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Malaysia Service</td>
        <td>0.60</td>
        <td>4.50</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Malaysia Utility</td>
        <td>0.55</td>
        <td>2.78</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Mexico Authentication</td>
        <td>0.65</td>
        <td>4.88</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Mexico Marketing</td>
        <td>1.15</td>
        <td>8.63</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Mexico Service</td>
        <td>0.30</td>
        <td>2.25</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Mexico Utility</td>
        <td>0.70</td>
        <td>2.03</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Netherlands Authentication</td>
        <td>1.90</td>
        <td>14.25</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Netherlands Marketing</td>
        <td>4.25</td>
        <td>31.88</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Netherlands Service</td>
        <td>2.35</td>
        <td>17.63</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Netherlands Utility</td>
        <td>2.10</td>
        <td>9.98</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Nigeria Authentication</td>
        <td>0.75</td>
        <td>5.63</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Nigeria Marketing</td>
        <td>1.35</td>
        <td>10.13</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Nigeria Service</td>
        <td>0.80</td>
        <td>6.00</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Nigeria Utility</td>
        <td>0.85</td>
        <td>1.35</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>North America Authentication</td>
        <td>0.35</td>
        <td>2.63</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>North America Marketing</td>
        <td>0.65</td>
        <td>4.88</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>North America Service</td>
        <td>0.25</td>
        <td>1.88</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>North America Utility</td>
        <td>0.40</td>
        <td>0.83</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Other Authentication</td>
        <td>0.80</td>
        <td>6.00</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Other Marketing</td>
        <td>1.60</td>
        <td>12.00</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Other Service</td>
        <td>0.40</td>
        <td>3.00</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Other Utility</td>
        <td>0.90</td>
        <td>1.50</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Pakistan Authentication</td>
        <td>0.60</td>
        <td>4.50</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Pakistan Marketing</td>
        <td>1.25</td>
        <td>9.38</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Pakistan Service</td>
        <td>0.40</td>
        <td>3.00</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Pakistan Utility</td>
        <td>0.65</td>
        <td>1.05</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Peru Authentication</td>
        <td>1.00</td>
        <td>7.50</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Peru Marketing</td>
        <td>1.85</td>
        <td>13.88</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Peru Service</td>
        <td>0.50</td>
        <td>3.75</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Peru Utility</td>
        <td>1.10</td>
        <td>3.98</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Rest of Africa Authentication</td>
        <td>0.40</td>
        <td>3.00</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Rest of Africa Marketing</td>
        <td>0.60</td>
        <td>4.50</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Rest of Africa Service</td>
        <td>0.95</td>
        <td>7.13</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Rest of Africa Utility</td>
        <td>0.40</td>
        <td>1.20</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Rest of Asia Pacific Authentication</td>
        <td>1.15</td>
        <td>8.63</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Rest of Asia Pacific Marketing</td>
        <td>1.95</td>
        <td>14.63</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Rest of Asia Pacific Service</td>
        <td>0.60</td>
        <td>4.50</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Rest of Asia Pacific Utility</td>
        <td>1.25</td>
        <td>3.15</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Rest of Central &amp; Eastern Europe Authentication</td>
        <td>1.50</td>
        <td>11.25</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Rest of Central &amp; Eastern Europe Marketing</td>
        <td>2.30</td>
        <td>17.25</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Rest of Central &amp; Eastern Europe Service</td>
        <td>0.65</td>
        <td>4.88</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Rest of Central &amp; Eastern Europe Utility</td>
        <td>1.65</td>
        <td>7.05</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Rest of Latin America Authentication</td>
        <td>1.20</td>
        <td>9.00</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Rest of Latin America Marketing</td>
        <td>1.95</td>
        <td>14.63</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Rest of Latin America Service</td>
        <td>1.10</td>
        <td>8.25</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Rest of Latin America Utility</td>
        <td>1.30</td>
        <td>2.25</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Rest of Middle East Authentication</td>
        <td>0.45</td>
        <td>3.38</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Rest of Middle East Marketing</td>
        <td>0.90</td>
        <td>6.75</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Rest of Middle East Service</td>
        <td>0.60</td>
        <td>4.50</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Rest of Middle East Utility</td>
        <td>0.55</td>
        <td>3.15</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Rest of Western Europe Authentication</td>
        <td>1.00</td>
        <td>7.50</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Rest of Western Europe Marketing</td>
        <td>1.55</td>
        <td>11.63</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Rest of Western Europe Service</td>
        <td>1.05</td>
        <td>7.88</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Rest of Western Europe Utility</td>
        <td>1.10</td>
        <td>6.00</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Russia Authentication</td>
        <td>1.15</td>
        <td>8.63</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Russia Marketing</td>
        <td>2.15</td>
        <td>16.13</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Russia Service</td>
        <td>1.05</td>
        <td>7.88</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Russia Utility</td>
        <td>1.25</td>
        <td>7.95</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Saudi Arabia Authentication</td>
        <td>0.60</td>
        <td>4.50</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Saudi Arabia Marketing</td>
        <td>1.10</td>
        <td>8.25</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Saudi Arabia Service</td>
        <td>0.50</td>
        <td>3.75</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Saudi Arabia Utility</td>
        <td>0.65</td>
        <td>2.33</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>South Africa Authentication</td>
        <td>0.50</td>
        <td>3.75</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>South Africa Marketing</td>
        <td>1.00</td>
        <td>7.50</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>South Africa Service</td>
        <td>0.45</td>
        <td>3.38</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>South Africa Utility</td>
        <td>0.55</td>
        <td>1.50</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Spain Authentication</td>
        <td>0.90</td>
        <td>6.75</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Spain Marketing</td>
        <td>1.65</td>
        <td>12.38</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Spain Service</td>
        <td>1.00</td>
        <td>7.50</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Spain Utility</td>
        <td>1.00</td>
        <td>3.98</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Turkey Authentication</td>
        <td>0.20</td>
        <td>1.50</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Turkey Marketing</td>
        <td>0.30</td>
        <td>2.25</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Turkey Service</td>
        <td>0.10</td>
        <td>0.75</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Turkey Utility</td>
        <td>0.25</td>
        <td>1.05</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>United Arab Emirates Authentication</td>
        <td>0.45</td>
        <td>3.38</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>United Arab Emirates Marketing</td>
        <td>0.90</td>
        <td>6.75</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>United Arab Emirates Service</td>
        <td>0.50</td>
        <td>3.75</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>United Arab Emirates Utility</td>
        <td>0.55</td>
        <td>3.15</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>United Kingdom Authentication</td>
        <td>0.95</td>
        <td>7.13</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>United Kingdom Marketing</td>
        <td>1.85</td>
        <td>13.88</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>United Kingdom Service</td>
        <td>1.05</td>
        <td>7.88</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>United Kingdom Utility</td>
        <td>1.05</td>
        <td>4.35</td>
    </tr>
    </tbody></table>
{: .reset-td-br-1 .reset-td-br-2}
{% enddetails %}

------

## SMS/MMS channel details

### SMS segments

SMS message segments are how the SMS industry counts messages. A message segment is a grouping of up to a defined number of characters (160 for GSM-7 encoding; 67 for UCS-2 encoding) that will be sent in a single SMS dispatch. If you dispatch an SMS with 161 characters using GSM-7 encoding, you will see that there are two (2) message segments that were sent. Sending multiple message segments will result in additional charges.

### MMS segments

For MMS, the message limit is 5 MB (this includes the multimedia asset and the message body size). To be on the safer side, Braze recommends not exceeding 600 KB for your multimedia asset while also including a message body.

## WhatsApp channel details

WhatsApp is a channel focused on two-way messaging and thus anchors on Conversations (instead of number of individual messages). A Conversation is a 24-hour thread between a business and an end-user.

### Conversation type definitions

**Marketing Conversations:** Business-initiated conversations that enable you to achieve a wide range of goals, from generating awareness to driving sales and retargeting customers. Examples include new product, service, or feature announcements, targeted promotions/offers, and cart abandonment reminders.

**Utility Conversations:** Business-initiated conversations that enable you to follow-up on user actions or requests. Examples include opt-in confirmation, order/delivery management (e.g., delivery update), account updates or alerts (e.g., payment reminder), or feedback surveys.

**Authentication Conversations:** Enable you to authenticate users with one-time passcodes, potentially at multiple steps in the login process (e.g., account verification, account recovery, integrity challenges).

{% alert note %}
Authentication conversations will only be supported on a case-by-case basis and Braze cannot guarantee specific SLAs. Additionally, Braze does not support PIN generation.
{% endalert %}

**Service Conversations:** User-initiated conversations that are responded to with a non-templated message.

{% alert note %}
User-initiated conversations that are responded to with a marketing or utility template will be charged as such.
{% endalert %}

## Billing region breakdown

#### North America

United States, Canada

#### Rest of Africa

Algeria, Angola, Benin, Botswana, Burkina Faso, Burundi, Cameroon, Chad, Congo, Eritrea, Ethiopia, Gabon, Gambia, Ghana,  Guinea-Bissau, Ivory Coast, Kenya, Lesotho, Liberia, Libya,
Madagascar, Malawi, Mali, Mauritania, Morocco, Mozambique, Namibia, Niger, Rwanda, Senegal, Sierra Leone, Somalia, South Sudan, Sudan, Swaziland, Tanzania, Togo, Tunisia, Uganda, Zambia

#### Rest of Asia Pacific

Afghanistan, Australia, Bangladesh, Cambodia, China, Hong Kong, Japan, Laos, Mongolia, Nepal, New Zealand, Papua New Guinea, Philippines, Singapore, Sri Lanka, Taiwan, Tajikistan, Thailand,
Turkmenistan, Uzbekistan, Vietnam

#### Rest of Central & Eastern Europe

Albania, Armenia, Azerbaijan, Belarus, Bulgaria, Croatia, Czech Republic, Georgia, Greece, Hungary, Latvia, Lithuania, Macedonia, Moldova, Poland, Romania, Serbia, Slovakia, Slovenia, Ukraine

#### Rest of Latin America

Bolivia, Costa Rica, Dominican Republic, Ecuador, El Salvador,
Guatemala, Haiti, Honduras, Jamaica, Nicaragua, Panama, Paraguay, Puerto Rico, Uruguay, Venezuela

#### Rest of Middle East

Bahrain, Iraq, Jordan, Kuwait, Lebanon, Oman, Qatar, Yemen

#### Rest of Western Europe

Austria, Belgium, Denmark, Finland, Ireland, Norway, Portugal, Sweden, Switzerland
