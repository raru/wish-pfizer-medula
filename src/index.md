---
title: "4721 - AWARENESS MEDULA OSSEA - BORA FALAR DE CANCÊR"
layout: "base.njk"
---
<section id="principal" class="container">
    <div id="boxes" class="grid grid-template-columns">
        <div class="item logo animate__animated animate__slideInLeft">
        {% EleventyImage "/images/logo_historiasparadoar.png", "Logo historias para Doar", "(min-width: 16em) 50vw, 100vw" %}</div>
        <div class="item gota animate__animated animate__fadeIn animate__delay-1s">
        {% EleventyImage "/images/icon_Gota.png", "Gota de sangue", "(min-width: 16em) 50vw, 100vw" %}</div>
        <div class="item txtvoce animate__animated animate__slideInRight">
        {% EleventyImage "/images/txt_voceedoadordemedulaossea.png", "Voce doador de medula ossea", "(min-width: 16em) 50vw, 100vw" %}</div>
        <div class="item mao  animate__animated animate__fadeIn animate__delay-1s">
        {% EleventyImage "/images/icon_mao.png", "mao", "(min-width: 16em) 50vw, 100vw" %}</div>
    </div>
    <div id="txt_bus" class="animate__animated animate__fadeInLeft animate__delay-1s"><p>Você está prestes a oferecer um futuro a muitas pessoas. Juntos, no dia 20 de setembro, nós, da Pfizer, vamos dizer sim à doação de medula óssea. <strong> Reserve o seu lugar e diga sim. </strong></p></div>
    <div id="oquefaremos" class="container grid grid-template-columns animate__animated animate__fadeIn animate__delay-3s">
        <div class="item img_oquefaremos">{% EleventyImage "/images/txt_oquefaremosjuntos.png", "O que faremos juntos", "(min-width: 16em) 50vw, 100vw" %}</div>
        <div class="item txt_oquefaremos"><p>
        <strong>1. Dizer sim!</strong> Ir a um hemocentro e cadastrar nossos dados pessoais no REDOME.<br/>
        <hr>
        <strong>2. Doar sangue.</strong> Doar uma pequena amostra de sangue para que possam nos identificar como doadores. *<br/>
        <hr>
        <strong>3. Esperar.</strong> Quando nossas características genéticas forem compatíveis às de alguém que esteja precisando de doação, seremos consultados e informados. <br/>
        </p>
        </div>
    </div>
    <small>Além da doação de medula, os hemocentros podem contar com a sua ajuda. Aproveite a nossa iniciativa para doar sangue também. Vamos multiplicar essa ação e dizer sim para salvar vidas sempre!</small><br/><br/>
</section>
<div style="clear:both"></div>
<section id="reserva"  >
    <div id="assentos" class="grid grid-template-columns-3">
        <div class="item"> {% EleventyImage "/images/bus_btn-selecione.png", "Logo historias para Doar", "(min-width: 16em) 50vw, 100vw" %} </div>
        <div class="item p20"> {% EleventyImage "/images/bus_btn-assentos_livres.png", "Logo historias para Doar", "(min-width: 16em) 50vw, 100vw" %} </div>
        <div class="item p20"> {% EleventyImage "/images/bus_btn-assentos_reservados.png", "Logo historias para Doar", "(min-width: 16em) 50vw, 100vw" %} </div>
    </div>
    <div id="bus">
        {% EleventyImage "/images/bus_bkg.png", "Logo historias para Doar", "(min-width: 16em) 50vw, 100vw" %}
    <!-- (A) SEAT LAYOUT -->
    <div id="layout"></div>
    <!-- (C) SAVE SELECTION -->
    <button id="save" onclick="reserve.save()">Reservar</button>        
    </div>
</section>