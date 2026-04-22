# Let's create your PIRs with Anomali ThreatStream Next-Gen
Priority Intelligence Requirements (PIRs) serve as the strategic foundation of any effective CTI program, ensuring that analyst effort and collection resources are directed toward the threats that matter most to the organization. Without clearly defined PIRs, security teams risk producing generic, unfocused intelligence that fails to inform real decision-making across SOC, IR, and executive stakeholders.
<br>

The article here is a quick guide how you can implement your PIRs with ThreatStream Next-Gen - Let’s get started!
<br>


## Create your priority intelligence questions list
First of all, you need to create a priority intelligence questions list tailored with your intelligence requirements. Hit *Reporting* on the left pane.
<br>
<div align="center">
<img src="./images/1.png" width=50%>
</div>
<br>
<br>

Hit *Template Management* tab on the top left, and hit *New Template* on the top right. Put an appropriate template name on the *Template Name* box, and put an appropriate description on the *Description* box. Define the report section and put those on *Sections* box, and hit *Create Template*.
<br>
<div align="center">
<img src="./images/2.png" width=50%>
</div>
<br>
<br>

After successful creation, you may see your reporting template. Let’s ask Copilot to create a priority intelligence questions list for you. Here comes a sample prompt for Copilot.
> Can you create the latest priority intelligence questions list for NTT Docomo Business?
<br>
<div align="center">
<img src="./images/3.png" width=50%>
</div>
<br>
<br>

Copilot is going to create a PIQ list, and it might ask you which reporting template you want to use. Tell the template name that you just created to Copilot.
<br>
<div align="center">
<img src="./images/4.png" width=50%>
</div>
<br>
<br>

In some minutes, a tailored priority intelligence questions list is going to be created. Now, you’re ready to create your PIRs. Let’s grab one of the questions that you just created.
<br>
<div align="center">
<img src="./images/5.png" width=50%>
</div>
<br>
<br>

Hit *Priority Intelligence Requirements* on the left pane, and hit *New PIR* on the top right.
<br>
<div align="center">
<img src="./images/6.png" width=50%>
</div>
<br>
<br>

Paste the priority intelligence question that you just grabbed on the *Description* box, and put an appropriate name on the *Name* box. Select appropriate *Category*, and specify *Stakeholders*, *Assignee* and *Priority*. Hit *Next*.
<br>
<div align="center">
<img src="./images/7.png" width=50%>
</div>
<br>
<br>

Copilot is going to analyze the contents that you just created on the privious screen, and going to associate relevant IoCs, Threat Models and Investigations to the PIR. Select any associations that you need to associate. Also, copilot is going to give you recommended tags and key words for the filtering. Select appropriat tags and key words so you can manage the PIR efficiently. Hit *Next*.
<br>
<div align="center">
<img src="./images/8.png" width=50%>
</div>
<br>
<br>

If you hit *Generate Analytics Process*, Copilot is going to analyze the contents that you just created on the previous screens, and create a suitable analytics process for the PIR. Hit it and *Next*.
<br>
<div align="center">
<img src="./images/9.png" width=50%>
</div>
<br>
<br>

You can also select output channels for the PIR. Let’s select *Email* for now, and specify a receiver. Hit *Next*.
<br>
<div align="center">
<img src="./images/10.png" width=50%>
</div>
<br>
<br>

If all settings are ok, you should hit *Create PIR*.
<br>
<div align="center">
<img src="./images/11.png" width=50%>
</div>
<br>
<br>

The PIR is created. The output is going to be emailed to the specified receiver with the defined cadence.
<br>
<div align="center">
<img src="./images/12.png" width=50%>
</div>
<br>
<br>
<br>
<br>

Hope the article is beneficial for you. If you have found a bug or if you have updates request, please create *Issues* - I'll follow-up accordingly.
