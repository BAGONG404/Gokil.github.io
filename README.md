<!DOCTYPE html>
<html>
  <head>
    <meta http—equiv="content—type" content="text/html; charset=utf—8" />
    <title>www</title>
    <link rel="stylesheet" type="text/css" href="z.css">
    <style type="text/css" media="all">
    body{
      background: black;
    }
      .jud{
        color: #00ff05ce;
        font-family: Times New Roman;
        font-size: 100px;
        margin-left: 300px;
      }
      .sub{
        color: #00ff05ce;
        font-family: Monospace;
        font-size: 50px;
        margin-left: 300px;
        margin-top: 200px;
      }
      .id1{
        width: 600px;
        height: 35px;
        margin-left: 80px;
        font-size: 20px;
        font-family: Monospace;
        border: #05f300 solid 5px;
        background: black;
        border-radius: 10px;
        color: white;
        margin-top: 50px;
      }
      .me{
        width: 600px;
        height: 35px;
        margin-left: 50px;
        font-size: 20px;
        font-family: Monospace;
        border: #05f300 solid 5px;
        background: black;
        border-radius: 10px;
        color: white;
        margin-top: 50px;
      }
      .id2{
        width: 150px;
        height: 75px;
        border: #05f300 solid 5px;
        border-radius: 30px;
        font-size: 30px;
        font-family: Monospace;
        color: #00ff05ce;
        background: black;
        margin-top: 50px;
        margin-left: 425px;
      }
      .me1{
        width: 150px;
        height: 75px;
        border: #05f300 solid 5px;
        border-radius: 30px;
        font-size: 30px;
        font-family: Monospace;
        color: #00ff05ce;
        background: black;
        margin-top: 50px;
        margin-left: 425px;
      }
      .hasil{
        width: 800px;
        margin-left: 100px;
        height: 300px;
        border: solid #05f300 5px ;
        border-radius: 50px;
        margin-top: 200px;
      }
      .tek{
        font-size: 18px;
        font-family: Monospace;
        color: #05f300;
        margin-left: 20px;
        margin-right: 20px;
        background: black;
        margin-top: 20px;
        border-color: black;
        width: 760px;
      }
    </style>
  </head>
  <body>
    <h1 class="jud"> MORSE </h1>
    <h2 class="sub">TEXT TO MORSE</h2>
    <p class="id4">
      Masukkan teks : <input type="text" id="text" class="id1">
    </p>
      <button onclick="submitdata()" class="id2">morse</button>
    <h2 class="sub">MORSE TO TEXT</h2>
    <p class="me3">
      Massukkan morse : <input type="text" id="me" class="me">
     </p>
      <button onclick="submitdata2()"class="me1">TEXT</button>
      <div id="hasil" class="hasil">
        <textarea id="tek" class="tek"></textarea>
        <p id="tek2" class="tek"></p>
      </div>
      <button onclick="copyText()" class="me1" type="submit">COPY</button>
    <script type="text/javascript" charset="utf—8">
    var text = document.getElementById('tek');
    function submitdata(){
    let aa = document.getElementById("text").value;
    var hasil = document.getElementById('hasil');
    console.log(aa);
    let kk = aa.replaceAll("space","/")
    let a = kk.replaceAll("a"," •— ");
    let b = a.replaceAll("b"," —••• ");
    let c = b.replaceAll("c"," —•—• ");
    let d = c.replaceAll("d"," —•• ");
    let e = d.replaceAll("e"," • ");
    let f = e.replaceAll("f"," ••—• ");
    let g = f.replaceAll("g"," ——• ");
    let h = g.replaceAll("h"," •••• ");
    let i = h.replaceAll("i"," •• ");
    let j = i.replaceAll("j"," •——— ");
    let k = j.replaceAll("k"," —•— ");
    let l = k.replaceAll("l"," •—•• ");
    let m = l.replaceAll("m"," —— ");
    let n = m.replaceAll("n"," —• ");
    let o = n.replaceAll("o"," ——— ");
    let p = o.replaceAll("p"," •——• ");
    let q = p.replaceAll("q"," ——•— ");
    let r = q.replaceAll("r"," •—• ");
    let s = r.replaceAll("s"," ••• ");
    let t = s.replaceAll("t"," — ");
    let u = t.replaceAll("u"," ••— ");
    let v = u.replaceAll("v"," •••— ");
    let w = v.replaceAll("w"," •—— ");
    let x = w.replaceAll("x"," —••— ");
    let y = x.replaceAll("y"," —•—— ");
    let z = y.replaceAll("z"," ——•• ");
    let kkk = y.replaceAll("space","/")
    let a2 = z.replaceAll("A"," •— ");
    let b2 = a2.replaceAll("B"," —••• ");
    let c2 = b2.replaceAll("C"," —•—• ");
    let d2 = c2.replaceAll("D"," —•• ");
    let e2 = d2.replaceAll("E"," • ");
    let f2 = e2.replaceAll("F"," ••—• ");
    let g2 = f2.replaceAll("G"," ——• ");
    let h2 = g2.replaceAll("H"," •••• ");
    let i2 = h2.replaceAll("I"," •• ");
    let j2 = i2.replaceAll("J"," •——— ");
    let k2 = j2.replaceAll("K"," —•— ");
    let l2 = k2.replaceAll("L"," •—•• ");
    let m2 = l2.replaceAll("M"," —— ");
    let n2 = m2.replaceAll("N"," —• ");
    let o2 = n2.replaceAll("O"," ——— ");
    let p2 = o2.replaceAll("P"," •——• ");
    let q2 = p2.replaceAll("Q"," ——•— ");
    let r2 = q2.replaceAll("R"," •—• ");
    let s2 = r2.replaceAll("S"," ••• ");
    let t2 = s2.replaceAll("T"," — ");
    let u2 = t2.replaceAll("U"," ••— ");
    let v2 = u2.replaceAll("V"," •••— ");
    let w2 = v2.replaceAll("W"," •—— ");
    let x2 = w2.replaceAll("X"," —••— ");
    let y2 = x2.replaceAll("Y"," —•—— ");
    let z2 = y2.replaceAll("Z"," ——•• ");
    let aa1 = z2.replaceAll("1"," •———— ");
    let aa2 = aa1.replaceAll("0"," ————— ");
    let aa3 = aa2.replaceAll("9"," ————• ");
    let aa4 = aa3.replaceAll("2"," ••——— ");
    let aa5 = aa4.replaceAll("8"," ———•• ");
    let aa6 = aa5.replaceAll("3"," •••—— ");
    let aa7 = aa6.replaceAll("7"," ——••• ");
    let aa8 = aa7.replaceAll("4"," ••••— ");
    let aa9 = aa8.replaceAll("5"," ••••• ");
    let aa10 = aa9.replaceAll("6"," —•••• ");
    text.textContent = aa10;
    }
    function submitdata2(){
      let a1 = document.getElementById("me").value;
    let ka = a1.replaceAll(".","•");
    let ku = ka.replaceAll("●","•");
    let pp = ka.replaceAll("_","—");
    let pp2 = pp.replaceAll("‐","—");
    let pp3 = pp2.replaceAll("–","—");
    let pp4 = pp3.replaceAll("—","—");
    let aa1 = pp4.replaceAll("•————","1");
    let aa2 = aa1.replaceAll("—————","0");
    let aa3 = aa2.replaceAll("————•","9");
    let aa4 = aa3.replaceAll("••———","2");
    let aa5 = aa4.replaceAll("———••","8");
    let aa6 = aa5.replaceAll("•••——","3");
    let aa7 = aa6.replaceAll("——•••","7");
    let aa8 = aa7.replaceAll("••••—","4");
    let aa9 = aa8.replaceAll("•••••","5");
    let aa10 = aa9.replaceAll("—••••","6");
    let ad= aa10.replaceAll("—•—•","c");
    let ah= aa10.replaceAll("••—•","f"); 
    let al= ah.replaceAll("••••","h");
    let an= al.replaceAll("•———","j");
    let ap= an.replaceAll("•—••","l");
    let at= ap.replaceAll("•——•","p");
    let au= at.replaceAll("——•—","q");
    let az= au.replaceAll("•••—","v");
    let bb= az.replaceAll("—••—","x");
    let bc= bb.replaceAll("—•——","y");
    let bd= bc.replaceAll("——••","z");
    let av= bd.replaceAll("•—•","r");
    let ba= av.replaceAll("•——","w");
    let ay= ba.replaceAll("••—","u");
    let aw= ay.replaceAll("•••","s");
    let as= aw.replaceAll("———","o");
    let ao= as.replaceAll("—•—","k");
    let ak= ao.replaceAll("•——","g");
    let ae= ak.replaceAll("—••","d");
    let aq= ae.replaceAll("——","m");
    let am= aq.replaceAll("••","i");
    let ar= am.replaceAll("—•","n");
    let ab= ar.replaceAll("•—","a");
    let ax= ab.replaceAll("—","t");
    let ag= ax.replaceAll(" • ","e");
    text.textContent = ag;
    }
    function copyText() {
      const textInput = document.getElementById("tek");
      textInput.select();
      textInput.setSelectionRange(0, 99999);
      navigator.clipboard.writeText(textInput.value)
    }
    submitdata();
    submitdata2();
    </script>
  </body>
</html>
