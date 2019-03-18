### CPSC 481 Group project - Restaurant reservation app/website
**Team memebers:**
* Akaljot Sangha
* Colin Thompson
* Tyson Wasylik
* Yu-Hsiang Wen (Sean)

<script>
  function pdf_click(id) {
    pdf = document.getElementById(id)
    if (pdf.style.display == "none")
      pdf.style.display = "block"
    else
      pdf.style.display = "none"
  }
  function p1_click() {
    p1_pdf = document.getElementById("p1_pdf")
    if (p1_pdf.style.display == "none")
      p1_pdf.style.display = "block"
    else
      p1_pdf.style.display = "none"
  }
  
  function p3_click() {
    p3_pdf = document.getElementById("p3_pdf")
    if (p3_pdf.style.display == "none")
      p3_pdf.style.display = "block"
    else
      p3_pdf.style.display = "none"
  }
</script>

### [P1 link](https://seavanas.github.io/CPSC481/team-acts__project_a1.pdf)
<button onclick="pdf_click('p1_pdf')">P1</button>
<embed id='p1_pdf' src='https://seavanas.github.io/CPSC481/team-acts__project_a1.pdf' width='100%' height='700px' style='display:none'>
<br>
### [P2 link](https://seavanas.github.io/CPSC481/p2.pdf)
<button onclick="pdf_click('p2_pdf')">P2</button>
<embed id='p2_pdf' src='https://seavanas.github.io/CPSC481/p2.pdf' type='application/pdf' width='100%' height='700px' style='display:none'>
### [P3 link](https://seavanas.github.io/CPSC481/p3.pdf)
<button onclick="pdf_click('p3_pdf')">P3</button>
<embed id='p3_pdf' src='https://seavanas.github.io/CPSC481/p3.pdf' type='application/pdf' width='100%' height='700px' style='display:none'>
