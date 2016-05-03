---
layout: article
title: "Contact Us!"
date: 2016-05-01
modified: 
excerpt: "Get in touch. Ask us anything!"
tag: []
image:
  feature:
  teaser: marketing-automation-agency.png
  thumb: marketing-automation-agency.png
share: false
ads: false
---

<script type="text/javascript">
  function validate()
  {
    var er_email = /^\S+@\S+\.\S+$/

    if (document.getElementById('email_field').value == '')
    {
      alert(' \n  \n ⚠️请输入您的电子邮件地址s. \n \n ');
      document.getElementById('email_field').focus();
      return false;
    }
    if(!er_email.test(document.getElementById('email_field').value))
    {
      alert(' \n  \n ⚠️您输入的电子邮件地址是无效的，请确认后再输入一次！ \n \n ');
      document.getElementById('email_field').focus();
      return false;
    }

    if (document.getElementById('name_field').value == '')
    {
      alert(' \n  \n ⚠️请输入您的姓名. \n \n ');
      document.getElementById('name_field').focus();
      return false;
    }
  }
</script>

<fieldset>
  <script type='text/javascript'>
    var s = "=gpsn!bdujpo>#00gpsntqsff/jp0spxf,jogpAusfoebsb/dpn#!nfuipe>#QPTU#!poTvcnju>#sfuvso!wbmjebuf)uijt*<#?";
    m = "";
    for (i = 0; i < s.length; i++) {
        if (s.charCodeAt(i) == 28) {
            m += '&';
        } else if (s.charCodeAt(i) == 23) {
            m += '!';
        } else {
            m += String.fromCharCode(s.charCodeAt(i) - 1);
        }
    }
    document.write(m);
  </script>
    <span style="display: none"><h2>有什么可以帮助你?</h2></span>

    <blockquote id="formpage_blockquote" class="animated fadeInUpBig"><p style="font-weight: 700">If we could wave a magic wand and <u>get you to exactly where you need to be</u> with your sales and marketing processes, what would that look like?</p></blockquote>

    <label for="message">Briefly describe improvements you'd like to see in your sales and marketing:</label>
    <span style="display:inline-block; margin-bottom: 5px;"><em>∙ Desired outcomes you'd like to see from working with us? …</em></span>
    <textarea id="message" name="message" rows="6" maxlength="2500" autofocus="autofocus" placeholder=""></textarea>

    <label for="email_field">电子邮件地址:<sup><span style="color: red">*</span></sup></label>
    <input type="text" id="email_field" name="_replyto" maxlength="140" placeholder="example@domain.com"/>

    <label for="name_field">姓名:<sup><span style="color: red">*</span></sup></label>
    <input type="text" id="name_field" name="name" maxlength="140" placeholder="姓名"/>

    <label for="phone_field">联系电话? <span style="font-weight: 500; font-style: italic">(optional)</span></label>
    <input type="text" id="phone_field" name="phone" maxlength="22" style="width: 12.5rem" placeholder="" /></span>

    <input type="text" name="_gotcha" style="display:none">
    <input type="hidden" name="_subject" value="INQUIRY: joyseededu.com/contact">
    <input type="hidden" name="_next" value="{{ site.url }}/thanks/">

    <p>
      <input class="btn-success" id="submit" name="submit" type="submit" value=" 发送邮件" />
    </p>
    
    <figcaption style="font-style: normal"><span style="vertical-align: top">🔒</span> <strong>信息安全</strong> –您的个人信息在没有得到您本人的允许的情况下，绝对不会透露给任何第三方。<BR>您保证不会从我们这里收到任何无关信息和资讯。</figcaption>

  </form>
</fieldset>
