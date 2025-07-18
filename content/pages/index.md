title: Home
slug: /
sections:
  - type: GenericSection
    title:
      text: Teška mehanizacija. Lako rješenje.
      color: text-dark
      type: TitleBlock
    subtitle: Strojevi koji rade za vas
    text: >
      Rock d.o.o. je vaša pouzdana adresa za prodaju bagera, utovarivača, traktora i druge građevinske mehanizacije. Nudimo provjerene strojeve, stručan savjet i brzu isporuku. Kod nas znate što kupujete – strojevi koji rade i traju.
    actions:
      - label: Pogledaj ponudu
        url: /#ponuda
        style: secondary
        icon: arrowRight
        iconPosition: right
        showIcon: true
        type: Button
      - label: Kontaktiraj nas
        url: /#kontakt
        style: primary
        icon: arrowRight
        iconPosition: right
        showIcon: true
        type: Link
    media:
      url: /images/main-hero.svg
      altText: Radni strojevi Rock d.o.o.
      type: ImageBlock
    badge:
      label: Strojevi koji pokreću posao
      color: text-primary
      type: Badge
    colors: bg-light-fg-dark
    styles:
      self:
        alignItems: center
        flexDirection: row
        padding:
          - pt-16
          - pl-16
          - pb-16
          - pr-16

  - type: FeaturedItemsSection
    title:
      text: Zašto Rock d.o.o.?
      color: text-dark
      type: TitleBlock
      styles:
        self:
          textAlign: center
    subtitle: Partner kojem vjerujete
    items:
      - title: 10+ godina iskustva
        subtitle: Znanje koje se isplati
        text: >
          Svaki naš stroj je provjeren, svaki kupac važan. Radimo brzo, pošteno i bez iznenađenja.
        image:
          url: /images/icon1.svg
          altText: Ikona iskustva
          type: ImageBlock
      - title: 100+ zadovoljnih klijenata
        subtitle: Povjerenje koje gradimo
        text: >
          Iza svakog bagera stoji ime. Iza svakog imena – mi.
        image:
          url: /images/icon2.svg
          altText: Ikona klijenta
          type: ImageBlock
      - title: Brza isporuka
        subtitle: Vrijeme je novac
        text: >
          Znamo da vam stroj treba jučer. Zato dostavljamo brzo i bez komplikacija.
        image:
          url: /images/icon3.svg
          altText: Ikona isporuke
          type: ImageBlock
    actions:
      - label: Saznaj više
        url: /#kontakt
        style: primary
        icon: arrowRight
        iconPosition: right
        showIcon: true
        type: Button
    badge:
      label: Naša snaga
      color: text-primary
      type: Badge
    variant: three-col-grid
    colors: bg-neutral-fg-dark
    styles:
      self:
        padding:
          - pt-16
          - pl-16
          - pb-16
          - pr-16

  - type: GenericSection
    title:
      text: Povežimo vas s pravim strojem
      color: text-dark
      type: TitleBlock
      styles:
        self:
          textAlign: center
    subtitle: Jer prava mašina mijenja sve
    text: >
      U Rock d.o.o. ne prodajemo samo strojeve – nudimo rješenja. Naš pristup je osoban, a ponuda fleksibilna. Bilo da gradite, prevozite ili obrađujete – imamo stroj za vas.
    media:
      url: /images/placeholder-video.mp4
      controls: false
      aspectRatio: '16:9'
      type: VideoBlock
      autoplay: true
      loop: true
      muted: true
      styles:
        self:
          padding:
            - pt-2
            - pb-2
            - pl-2
            - pr-2
          borderColor: border-dark
          borderStyle: solid
          borderWidth: 1
          borderRadius: large
    badge:
      label: Naša vizija
      color: text-primary
      type: Badge
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pt-16
          - pb-16
          - pl-16
          - pr-16
        flexDirection: col
        justifyContent: center

  - type: GenericSection
    title:
      text: Usluge
      color: text-dark
      type: TitleBlock
    subtitle: Više od prodaje
    text: >
      ✔️ Prodaja novih i polovnih strojeva  
      ✔️ Savjetovanje prije kupnje  
      ✔️ Pronalazak i nabava po narudžbi  
      ✔️ Dostava širom regije  
      
      Sve na jednom mjestu. Bez komplikacija.
    media:
      url: /images/hero2.svg
      altText: Usluge Rock d.o.o.
      type: ImageBlock
    badge:
      label: Naša ponuda
      color: text-primary
      type: Badge
    colors: bg-light-fg-dark
    styles:
      self:
        alignItems: center
        flexDirection: row

  - type: GenericSection
    title:
      text: Pošaljite nam upit
      color: text-dark
      type: TitleBlock
    subtitle: Tu smo za svako pitanje
    text: >
      Bilo da tražite ponudu, stroj ili savjet — javite nam se. Odgovaramo brzo i konkretno.
    media:
      fields:
        - name: name
          label: Ime
          placeholder: Vaše ime
          isRequired: true
          width: full
          type: TextFormControl
        - name: email
          label: Email
          placeholder: Vaš email
          isRequired: true
          width: full
          type: EmailFormControl
        - name: message
          label: Poruka
          placeholder: Napišite nam poruku
          width: full
          type: TextareaFormControl
      elementId: kontakt-form
      type: FormBlock
      styles:
        self:
          padding:
            - pt-6
            - pb-6
            - pl-6
            - pr-6
          borderColor: border-dark
          borderStyle: solid
          borderWidth: 1
          borderRadius: large
      submitButton:
        label: Pošalji
        style: primary
        type: SubmitButtonFormControl
        icon: arrowRight
        showIcon: true
    badge:
      label: Kontaktiraj nas
      color: text-primary
      type: Badge
    colors: bg-light-fg-dark
