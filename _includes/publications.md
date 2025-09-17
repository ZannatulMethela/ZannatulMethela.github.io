<!--<h2 id="publications" style="margin: 2px 0px -15px;">Publications</h2>

<div class="publications">
<ol class="bibliography">

{% for link in site.data.publications.main %}

<li>
<div class="pub-row">
  <div class="col-sm-3 abbr" style="position: relative;padding-right: 15px;padding-left: 15px;">
    {% if link.image %} 
    <img src="{{ link.image }}" class="teaser img-fluid z-depth-1" style="width=100;height=40%">
    {% if link.conference_short %} 
    <abbr class="badge">{{ link.conference_short }}</abbr>
    {% endif %}
    {% endif %}
  </div>
  <div class="col-sm-9" style="position: relative;padding-right: 15px;padding-left: 20px;">
      <div class="title"><a href="{{ link.pdf }}">{{ link.title }}</a></div>
      <div class="author">{{ link.authors }}</div>
      <div class="periodical"><em>{{ link.conference }}</em>
      </div>
    <div class="links">
      {% if link.pdf %} 
      <a href="{{ link.pdf }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">PDF</a>
      {% endif %}
      {% if link.code %} 
      <a href="{{ link.code }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">Code</a>
      {% endif %}
      {% if link.page %} 
      <a href="{{ link.page }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">Project Page</a>
      {% endif %}
      {% if link.bibtex %} 
      <a href="{{ link.bibtex }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">BibTex</a>
      {% endif %}
      {% if link.notes %} 
      <strong> <i style="color:#e74d3c">{{ link.notes }}</i></strong>
      {% endif %}
      {% if link.others %} 
      {{ link.others }}
      {% endif %}
    </div>
  </div>
</div>
</li>
<br>

{% endfor %}

</ol>
</div>
-->

<h2 id="publications" style="margin: 2px 0px -15px;">Publications</h2>

<div class="publications">
  <ol class="bibliography">
    
    <li>
  <div class="pub-row">
    <div class="col-sm-3 abbr" style="position: relative;padding-right: 15px;padding-left: 15px;">
      <img src="assets\img\education.png" class="teaser img-fluid z-depth-1" style="width=100;height=40%">
      <abbr class="badge">ICICT 2024</abbr>
    </div>
    <div class="col-sm-9" style="position: relative;padding-right: 15px;padding-left: 20px;">
      <div class="title"><a href="https://ieeexplore.ieee.org/abstract/document/10839727">Integrating Feature Selection and Extraction with Tuned Multilayer Perceptrons for Predicting Student Dropout Risk in Higher Education</a></div>
      <div class="author"><strong>Zannatul Ferdousee</strong>, Md Rakibul Haque</div>
      <div class="periodical"><em>IEEE 2nd International Conference on Information and Communication Technology (ICICT), 2024 <strong>(Accepted)</strong></em></div>
      <div class="links">
        <!-- Add PDF link when available -->
         <a href="assets/files/educational.pdf" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">PDF</a>
      </div>
    </div>
  </div>
</li>
<br>



    <li>
      <div class="pub-row">
        <div class="col-sm-3 abbr" style="position: relative;padding-right: 15px;padding-left: 15px;">
          <img src="assets\img\covid_19.png" class="teaser img-fluid z-depth-1" style="width=100;height=40%">
          <abbr class="badge">ICEEICT 2024</abbr>
        </div>
        <div class="col-sm-9" style="position: relative;padding-right: 15px;padding-left: 20px;">
          <div class="title"><a href="https://ieeexplore.ieee.org/document/10534572">Deep Transfer Learning Based Approaches for Classification of Chest CT Scans: Normal, COVID-19, and Pneumonia</a></div>
          <div class="author">Morseda Siddiqua, <strong>Zannatul Ferdousee</strong></div>
          <div class="periodical"><em>IEEE 6th International Conference on Electrical Engineering and Information & Communication Technology (ICEEICT), 2024</em></div>
          <div class="links">
            <a href="assets/files/Covid_19.pdf" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">PDF</a>
          </div>
        </div>
      </div>
    </li>
    <br>

    
    
    <li>
      <div class="pub-row">
        <div class="col-sm-3 abbr" style="position: relative;padding-right: 15px;padding-left: 15px;">
          <img src="assets\img\propionylation.png" class="teaser img-fluid z-depth-1" style="width=100;height=40%">
          <abbr class="badge">ICCIT 2023</abbr>
        </div>
        <div class="col-sm-9" style="position: relative;padding-right: 15px;padding-left: 20px;">
          <div class="title"><a href="https://ieeexplore.ieee.org/document/10441189">Propionylation Characterization Ensembling Classifiers on Varied Features</a></div>
          <div class="author"><strong>Zannatul Ferdousee</strong>, S M Shovan, MD Sharifujjaman</div>
          <div class="periodical"><em>IEEE 26th International Conference on Computer and Information Technology (ICCIT), 2023</em></div>
          <div class="links">
            <a href="assets/files/Propionylation.pdf" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">PDF</a>
          </div>
        </div>
      </div>
    </li>
    <br>
    
    <!-- Add additional publications similarly below -->

    <li>
      <div class="pub-row">
        <div class="col-sm-3 abbr" style="position: relative;padding-right: 15px;padding-left: 15px;">
          <img src="assets\img\Breast.jpg" class="teaser img-fluid z-depth-1" style="width=100;height=40%">
          <abbr class="badge">ICCIT 2023</abbr>
        </div>
        <div class="col-sm-9" style="position: relative;padding-right: 15px;padding-left: 20px;">
          <div class="title"><a href="https://ieeexplore.ieee.org/document/10441637">Transfer Learning Based Approaches for Breast Cancer Classification using Mammogram Images</a></div>
          <div class="author">MD Sharifujjaman, <strong>Zannatul Ferdousee</strong>, Nahin Ul Sadad, Boshir Ahmed</div>
          <div class="periodical"><em>IEEE 26th International Conference on Computer and Information Technology (ICCIT), 2023</em></div>
          <div class="links">
            <a href="assets/files/Breast_Cancer.pdf" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">PDF</a>
            
            
          </div>
        </div>
      </div>
    </li>
    <br>
    
  </ol>
</div>


