---
title: "Clinical Trials"
subtitle: Recent clinical trials for multiple sclerosis treatments
date: 2021-02-24T13:25:38Z
lastmod: 
author: Bruno Amaral
options:
  unlisted: false
  header: mini
  navbar: navbar navbar-expand-lg bg-white fixed-top font-weight-bold

description: 
categories: []
tags: []

draft: false
enableDisqus : true
enableMathJax: false
disableToC: false
disableAutoCollapse: true

menu:
    main:
        Name: Clinical Trials
        weight: 7

resources:
  - src: science-in-hd-9kSTF9PvETM-unsplash.jpeg
    name: header

---
<div class="row">
<div class="col-12 justify-content-center align-self-center align-center text-center pb-5">
<a href="https://metabase.gregory-ms.com/public/dashboard/497ab618-6921-4eab-b0c5-878deeba69d9" id="metabaseDashboard" data-umami-event="click--body-metabase-dashboard-trials" class="btn btn-lg btn-primary" target="_blank">Open the Dashboard of Clinical Trials for Multiple Sclerosis <i class=" text-white fas fa-external-link-square-alt" aria-hidden="true"></i></a>
</div>
</div>

<div class="row">
<div class="col-md-6 justify-content-center align-self-center align-right ">
<img src="/trials/undraw_mail_re_duel.svg" class="w-75 float-right">
</div>
<div class="col-md-6 ml-auto mr-auto mb-5">
	<div class="card card-contact card-raised">
		<form role="form" id="contact-form1" method="post" action="https://api.gregory-ms.com/subscriptions/new/">
			<div class="card-header text-center">
				<h4 class="card-title font-weight-bold">Notification of new clinical trials</h4>
				<p class="p-3">Everyone has access to a free service that sends an email everytime a new clinical trial is posted on <a href="https://clinicaltrials.gov/ct2/results/rss.xml?rcv_d=14&lup_d=&sel_rss=new14&cond=Multiple+Sclerosis&count=10000">ClinicalTrials.gov</a> or in <a href="https://www.clinicaltrialsregister.eu/ctr-search/rest/feed/bydates?query=multiple+AND+sclerosis">Clinicaltrialsregister.eu</a></p>
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
							<option value="patient">patient</option>
							<option value="doctor">doctor</option>
							<option value="clinical centre">clinical centre</option>
						</select>
					</div>
				</div>
				<div class="row">
					<div class="col-md-12 ml-auto mr-auto text-center">
						<input value="1" name="list" id="list" type="hidden">
						<button type="submit" class="btn btn-primary btn-round mr-auto ml-auto font-weight-bold">Subscribe</button>
					</div>
				</div>
			</div>
		</form>
	</div>
</div>
</div>

<div class="col-12 align-content-center text-center">
<h2 class="title" id="clinical-trial">Recent Clinical Trials for Multiple Sclerosis</h2>

<p>Multiple Sclerosis Trials listed are retrieved from <a target="_blank" href="https://www.cuf.pt/cuf-academic-center/ensaios-clinicos?combine=&unidade=&estado=All&patologia=2346&especialidade=">CUF <i class="text-muted text-primary fas fa-external-link-square-alt"></i></a> &nbsp;
  <a target="_blank" href="https://clinicaltrials.gov/ct2/results/rss.xml?rcv_d=14&lup_d=&sel_rss=new14&cond=Multiple+Sclerosis&count=10000">ClinicalTrials.gov <i class="text-muted text-primary fas fa-external-link-square-alt"></i></a> &nbsp;
  <a target="_blank" href="https://www.novartis.com/clinicaltrials/recruiting-trials?title=multiple%20sclerosis">Novartis <i class="text-muted text-primary fas fa-external-link-square-alt"></i></a> &nbsp;
	<a href="https://www.clinicaltrialsregister.eu/ctr-search/rest/feed/bydates?query=multiple+AND+sclerosis">Clinicaltrialsregister.eu <i class="text-muted text-primary fas fa-external-link-square-alt"></i></a>
</p>

</div>

{{< trials >}}