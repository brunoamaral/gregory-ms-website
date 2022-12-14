---
authors:
  - bruno-amaral
date: 2021-09-23T20:37:07+01:00
description: ""
draft: false
layout: page
rowclasses: justify-content-center align-self-center
resources: 
- src: images/national-cancer-institute-NFvdKIhxYlU-unsplash.jpeg
  name: "header"
- src: "gallery/*.jpg"
  name: gallery-:counter
  title: gallery-title-:counter
- src:
  name: slide-1
slug:
subtitle: "This site exists to save you time in finding the latest research to help your patients."
tags: 
  - 
categories: 
  - 
title: "For Doctors"
menu:
  main:
    weight: 2
    name: Doctors
options:
  unlisted: false
  showHeader: true
  hideFooter: false
  hideSubscribeForm: false
  header: mini
scripts:
  - '<script src="/js/mermaid.min.js"></script>'
---
</div>
<div class="row justify-content-center align-self-center mb-5 p-md-5 mb-5">
<div class="col-md-5 col-12 justify-content-center align-self-center align-left">
  <h3 class="title">Promising articles for patient outcomes</h3>
  <p class="lead font-weight-biold">View online or download the full listing.</p>
  <a href='/developers/articles.zip' target="_blank" class="btn btn-primary btn-round btn-lg font-weight-bold umami--click--doctors-page-download-articles-zip"> Download Articles <i class="ml-1 fas fa-file-archive"></i></a>
  <a href='/relevant/' class="btn btn-info btn-round btn-lg font-weight-bold umami--click--doctors-page-download-articles-zip"> View online <i class="ml-1 fas fa-arrow-circle-right"></i></a>
  </div>
<div class="col-md-5 col-12 align-self-center">
  <img src="images/undraw_export_files_re_99ar.svg" class="w-50 align-middle d-none d-md-block ml-auto mr-auto" alt="Email newsletter" loading="lazy" />
</div>  



<div class="col-md-4 col-12 justify-content-center align-self-center align-right mt-5">
  <img src="images/undraw_medicine_b1ol.svg" class="w-75 align-middle d-none d-md-block" alt="medical doctors" loading="lazy"/>
  </div>
  <div class="col-md-5 col-12 justify-content-center align-self-center mt-5">  
  <h3 class="title">The observatory</h3>
  <p class="lead font-weight-biold">On this page you will find a listing of promissing medicine and therapies with their associated articles and clinical trials.</p>
  <p>An item is added to the list based on what is identified by the MS Society Website, or when there is an associated clinical trial.</p>
  <a href='{{< ref "/observatory/_index.md" >}}' class="btn btn-success btn-round btn-lg font-weight-bold umami--click--doctors-page-observatory">Observatory <i class="mr-1 fas fa-arrow-circle-right"></i></a>
  
  </div>
</div>

<div class="row justify-content-center align-self-center mb-5 p-md-5">
<div class="col-md-5 col-12 justify-content-center align-self-center ">
  <div class="col-md-12 ml-auto mr-auto">
              <div class="card card-contact card-raised">
                <form role="form" id="contact-form1" method="post" action="https://api.gregory-ms.com/subscriptions/new/">
                  <div class="card-header text-center">
                    <h4 class="card-title font-weight-bold">Weekly digest of relevant papers</h4>
                    <p class="p-3">Every tuesday, and email with the latest research filtered by Machine Learning and human review.</p>
                  </div>
                  <div class="card-body">
                    <div class="row">
                      <div class="col-md-6 pr-2">
                        <label>First name</label>
                        <div class="input-group">
                          <div class="input-group-prepend">
                            <span class="input-group-text pr-2"><i class="now-ui-icons users_circle-08"></i></span>
                          </div>
                          <input type="text" name="first_name" class="form-control" placeholder="First Name..." aria-label="First Name..." autocomplete="given-name">
                        </div>
                      </div>
                      <div class="col-md-6 pl-2">
                        <div class="form-group">
                          <label>Last name</label>
                          <div class="input-group">
                            <div class="input-group-prepend">
                              <span class="input-group-text pr-2"><i class="now-ui-icons text_caps-small"></i></span>
                            </div>
                            <input type="text" name="last_name" class="form-control" placeholder="Last Name..." aria-label="Last Name..." autocomplete="family-name">
                          </div>
                        </div>
                      </div>
                    </div>
                    <div class="form-group">
                      <label>Email address</label>
                      <div class="input-group">
                        <div class="input-group-prepend">
                          <span class="input-group-text pr-2"><i class="now-ui-icons ui-1_email-85"></i></span>
                        </div>
                        <input type="email" name="email" id="email" class="form-control" placeholder="Email Here..." autocomplete="email">
                      </div>
                    </div>
                    <div class="form-group">
                      <label>I am a...</label>
                      <div class="input-group">
                        <select id="profile" name="profile" class="form-control">
                          <option value="doctor">doctor</option>
                          <option value="researcher">researcher</option>
                          <option value="clinical centre">clinical centre</option>
                          <option value="patient">patient</option>
                        </select>
                      </div>
                    </div>
                    <div class="row">
                      <div class="col-md-12 ml-auto mr-auto text-center">
                        <input value="2" name="list" id="list" type="hidden">
                        <button type="submit" class="btn btn-primary btn-round mr-auto ml-auto">Subscribe</button>
                      </div>
                    </div>
                  </div>
                </form>
              </div>
            </div>
</div>
  <div class="col-md-5 col-12 align-self-center">
    <img src="images/undraw_subscribe_vspl.svg" class="w-50 align-middle d-none d-md-block ml-auto mr-auto" alt="Email newsletter" loading="lazy" />
  </div>  
</div>


<div class="row justify-content-center align-self-center mb-5 p-md-5">
  <div class="col-md-4 col-12 align-self-center">
    <img src="images/undraw_medical_research_qg4d.svg" class="w-75 align-middle d-none d-md-block" alt="Email newsletter" loading="lazy" />
  </div>
  <div class="col-md-5 col-12 justify-content-center align-self-center">
    <h3 class="title">Clinical Trials</h3>
    <p class="lead font-weight-biold">We do the best we can to identify clinical trials for Multiple Sclerosis and list them.</p>
    <a href='{{< ref "/trials/_index.md" >}}' class="btn btn-success btn-round btn-lg font-weight-bold umami--click--doctors-page-view-trials">View latest clinical trials <i class="ml-1 fas fa-arrow-circle-right"></i></a>
    </div>
</div>

<div class="row justify-content-center align-self-center mb-5 p-md-5">
<div class="col-md-12"><h3 class="title text-center">Where the information comes from</h3></div>
<div class="mermaid col-md-10 mx-auto">
graph TD;
    APTA[fa:fa-newspaper APTA.org] -->Gregory;
    BioMedCentral[fa:fa-newspaper BioMedCentral.com] -->Gregory;
    JNeurosci[fa:fa-newspaper JNeurosci.org]-->Gregory;
    PEDro[fa:fa-newspaper PEDro.org.au] -->Gregory;
    PubMed[fa:fa-newspaper PubMed.gov] -->Gregory;
    Reuters[fa:fa-newspaper Reuters Health]-->Gregory;
    Scielo[fa:fa-newspaper Scielo.org] -->Gregory;
    TheLancet[fa:fa-newspaper The Lancet Health]-->Gregory;
    MsRelDis[fa:fa-newspaper MS and Related Disorders]-->Gregory;
    Manual[fa:fa-keyboard Manual Input]-->Gregory;
    Gregory{fa:fa-robot Gregory}-->Website(fa:fa-globe Website)
    Gregory{fa:fa-robot Gregory}-->Newsletter(fa:fa-envelope Newsletter)
</div>
<div class="col-md-12 text-center">
  <a href='{{< ref "/about/index.md" >}}' class="btn btn-primary btn-round btn-lg font-weight-bold umami--click--doctors-page-link-about-page">More information on the about page <i class="fas fa-arrow-circle-right"></i></a>
</div>
</div>

