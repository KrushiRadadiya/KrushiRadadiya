
.privacy_prompt_analytics {
    z-index: 10000 ! important;
    /* position: absolute ! important; */
    /* left: 12% ! important; */
    /* right: 25% ! important; */
    height: auto ! important;
    margin: 0 ! important;
    padding: 15px 45px 45px ! important;
    background-color: #f2fafd ! important;
    box-sizing: border-box ! important;
    /* overflow-y: hidden ! important; */
    width: 61% ! important;
    box-shadow: 0 0 60px 0 rgba(0,0,0,0.3) ! important;
    text-align: left ! important;
    display: none;
    max-height: 95vh ! important;
    overflow-y: auto ! important;
    position: fixed ! important;
    border-radius: 10px;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
}

.privacy_prompt_analytics.is-active {
    /*top: 20px ! important;*/
    transition: 0.3s
}

.privacy_prompt_content_analytics{
    padding-right: 50px ! important;
    margin-bottom: 40px ! important;
}


.privacy_prompt_analytics * {
    color: #544F40 ! important;
    font-family: Arial, serif ! important;
    letter-spacing: 0.25px ! important;
    font-size: 16px ! important;
    line-height: 1.7 ! important;
    font-weight: normal ! important;
}

.privacy_prompt_analytics p {
    margin: 0 0 20px 8px ! important;
    max-width: none ! important;
}
.privacy_policy_url {
    font-weight: bold ! important;
    text-decoration: underline;
    color: #15717D !important;
    display: inline-block !important;
}
.privacy_prompt_title_analytics {
    font-size: 28px ! important;
    font-weight: bold ! important;
    padding-left: 8px ! important;
    margin: 10px 0 ! important;
    border-bottom: none ! important;
    padding-bottom: unset ! important;
    text-align: left ! important;
}

.privacy_prompt_analytics .option_set_analytics {
    display: -webkit-flex;
    display: flex;
    -webkit-flex-direction: row ! important;
    flex-direction: row ! important;
    -webkit-flex-wrap: nowrap ! important;
    flex-wrap: nowrap ! important;
    -webkit-justify-content: flex-start ! important;
    justify-content: flex-start ! important;
    -webkit-align-items: baseline ! important;
    align-items: baseline ! important;
    -webkit-align-content: flex-start ! important;
    align-content: flex-start ! important;
}

.privacy_prompt_analytics .option_set_analytics .option_set__checkbox_analytics {
    margin-right: 20px ! important;
}

.privacy_prompt_analytics .option_set_analytics .option_set__checkbox_analytics input {
    -webkit-transform: scale(1.2) translateZ(0) ! important;
    transform: scale(1.2) translateZ(0) ! important;
    height: auto ! important;
    width: auto ! important;
    opacity: 1 ! important;
}

.privacy_prompt_analytics .show_more_analytics {
    display: -webkit-flext;
    display: flex;
    /* -webkit-justify-content: flex-end ! important; */
    /* justify-content: flex-end ! important; */
    margin: 10px 0px ! important;
    float: left ! important;
}

.privacy_prompt_analytics .prompt_click_analytics {
    float: right ! important;
}

.privacy_prompt_analytics .show_more_analytics a {
    display: none;
    font-weight: bold ! important;
}

.privacy_prompt_analytics .show_more_analytics a.is-active {
    display: block;
}

.privacy_prompt_analytics .show_more_description_analytics {
    display: block;
    overflow: hidden ! important;
    height: auto ! important;
    max-height: 0 ! important;
    transition: 300ms ! important;
}

.privacy_prompt_analytics .show_more_description_analytics.is-active {
    max-height: 2500px ! important;
    transition: 300ms ! important;
}

.privacy_prompt_analytics .show_more_description_analytics ul {
    padding: 0 ! important;
    margin: 0 ! important;
}

.privacy_prompt_analytics .show_more_description_analytics ul li {
    list-style: none ! important;
    margin: 0 ! important;
}
.privacy_prompt_analytics .show_more_description_analytics ul li:before{
    content: "" ! important;
    margin-left: 0px ! important;
}

.privacy_prompt_analytics .show_more_description_analytics ul p {
    margin-top: 0px ! important;
}

.privacy_prompt_analytics .show_more_description_analytics .cookie_description__title_analytics {
    font-weight: bold ! important;
    display: inline-block;
}

.cookie_description__container_analytics .toggle_analytics{
    margin: 0px 11px 11px 0px ! important;
    position: unset ! important;
    padding: 0px 8px;
}


.privacy_prompt_analytics .show_more_description_analytics ul .cookie_description_paragraph_analytics {
    margin-left: 34px ! important; 
}

.privacy_prompt_analytics .cookie_description__container_analytics p{
    margin-left: 0px ! important; 
}

.privacy_prompt_analytics .preferences_prompt_submit_analytics,
.privacy_prompt_analytics .preferences_prompt_unchecked_submit_analytics {
    padding: 12px 16px ! important;
    width: auto ! important;
    height: 40px ! important;
    box-sizing: border-box ! important;
    text-align: center ! important;
    margin: 5px 0 0 16px ! important;
    float: none ! important;
    font-weight: bold ! important;
    position: initial ! important;
    letter-spacing: 1.5px ! important;
    font-size: 12px ! important;
    display: inline;
    border: 2px solid #E31836 !important;
    text-transform: uppercase ! important;
    border-radius: 8px;
}

#preferences_prompt_decline {
    background-color: #fff ! important;
    color: #E31836 !important;
}

#preferences_prompt_submit {
    background-color: #E31836 !important;
    color: #fff ! important;
}

.privacy_prompt_analytics .preferences_prompt_submit_analytics:hover,
.privacy_prompt_analytics .preferences_prompt_unchecked_submit_analytics:hover {
    cursor: pointer ! important;
}

.preferences_prompt_control_analytics {
    z-index: 10000 ! important;
    position: fixed ! important;
    bottom: -30px ! important;
    left: -30px ! important;
    cursor: pointer ! important;
}

.preferences_prompt_control_analytics .configuration_icon_selected_analytics {
    background: #fff ! important;
}

.preferences_prompt_control_analytics .configuration_icon_not_selected_analytics {
    background: #17717d ! important;
}

.preferences_prompt_control_analytics .configuration_icon_not_selected_analytics,
.preferences_prompt_control_analytics .configuration_icon_selected_analytics {
    height: 60px ! important;
    width: 60px ! important;
    -webkit-transform: rotate(45deg) ! important;
    transform: rotate(45deg) ! important;
    display: none;
}

.preferences_prompt_control_analytics .configuration_icon_not_selected_analytics.is-active,
.preferences_prompt_control_analytics .configuration_icon_selected_analytics.is-active {
    display: block;
}

.preferences_prompt_control_analytics .configuration_icon_not_selected_analytics img,
.preferences_prompt_control_analytics .configuration_icon_selected_analytics img {
    width: 12px ! important;
    height: 12px ! important;
    padding: 6px 0 0 25px ! important;
    box-sizing: content-box ! important;
}

.click_analytics:after {
    content:none ! important;
}

#privacy_prompt_background {
    position: fixed ! important;
    top: 0 ! important;
    left: 0 ! important;
    background: #555555 ! important;
    z-index: 9999 ! important;
    width: 100% ! important;
    height: 100% ! important;
    opacity: 0.8 ! important;
    display: none;
}

.show_more_less_analytics {
    margin-left: 8px ! important;
    color: #544F40 ! important;
    font-weight: bold ! important;
    display: inline-block;
    transform: rotate(270deg) ! important;
}

#show-less-icon {
    display: none;
    transform: rotate(90deg) ! important;
}

span#show-more-icon::before {
    content: '❮';
    font-size: 16px;
    position: absolute;
    top: -5px;
    left: 0;
}

span#show-less-icon::before {
    content: '❮';
    font-size: 16px;
    position: absolute;
    bottom: -5px;
    right: 0;
}


.cookie_banner_checkbox_analytics {
    /*display: inline-block;*/
    position: relative ! important;
    cursor: pointer ! important;
    height: 16px ! important;
    width: 16px ! important;
    /*display: unset ! important;*/
    display: inline ! important;
    margin-left: 0px ! important;
}

.cookie_banner_checkbox_analytics input {
    opacity: 0 ! important;
    height: unset ! important;
    width: unset ! important;
}

.cookie_banner_checkbox_analytics .checkbox_tick_analytics {
    position: absolute ! important;
    top: -2px ! important;
    left: 0px ! important;
    height: 16px ! important;
    width: 16px ! important;
    background-color: transparent ! important;
    border-radius: 2px ! important;
    border: 1.5px solid #544F40 ! important;
    box-sizing: unset ! important;
}


.cookie_banner_checkbox_analytics input:checked ~ .checkbox_tick_analytics {
    background-color: #15717D ! important;
    border: 1.5px solid #15717D ! important;
    border-radius: 2px ! important;
    opacity: 1 ! important;
}


.cookie_banner_checkbox_analytics .checkbox_tick_analytics::after {
    position: absolute ! important;
    content: "" ! important;
    left: 12px ! important;
    top: 12px ! important;
    height: 0px ! important;
    width: 0px ! important;
    border-radius: 2px ! important;
    border: solid #15717D ! important;
    border-width: 0 3px 3px 0 ! important;
    -webkit-transform: rotate(0deg) scale(0) ! important;
    -ms-transform: rotate(0deg) scale(0) ! important;
    transform: rotate(0deg) scale(0) ! important;
    opacity: 1 ! important;
    -webkit-box-sizing: border-box;
    box-sizing: border-box;
}


.cookie_banner_checkbox_analytics input:checked ~ .checkbox_tick_analytics::after {
    -webkit-transform: rotate(45deg) scale(1) ! important;
    -ms-transform: rotate(45deg) scale(1) ! important;
    transform: rotate(45deg) scale(1) ! important;
    opacity: 1 ! important;
    left: 0 ! important;
    top: 0 ! important;
    /* bottom: 0 ! important; */
    right: 0 ! important;
    margin: auto ! important;
    width: 6px ! important;
    height: 12px ! important;
    border: solid #FFFFFF ! important;
    border-width: 0 2px 2px 0 ! important;
    background-color: transparent ! important;
    border-radius: 0 ! important;
    -webkit-box-sizing: border-box;
    box-sizing: border-box;
}
    #show-more, #show-less {
        text-decoration: none ! important;
        outline: none ! important;
    }
.preferences_prompt_submit_analytics:hover {
    background-color: #E31836 !important;
    color: #FFFFFF ! important;
    box-shadow: 0 0 10px 0 rgba(0,0,0,0.3) ! important;
}

@media only screen and (max-width: 767px) {
    .privacy_prompt_analytics {
        bottom: -812px ! important;
        top: unset ! important;
        left: 0% ! important;
        right: 0% ! important;
        width: 100% ! important;
        padding: 31px 20px ! important;
        transform: none;
    }
    #privacy_prompt{
        position: fixed ! important;
        top: inherit ! important;
        bottom:0 ! important;
}
    .privacy_prompt_analytics.is-active {
        top: 0 ! important;
        transition: bottom 0.3s ! important;
        max-height: 100vh ! important;
        overflow-y: scroll ! important;
    }
    
    .privacy_prompt_content_analytics {
        padding-right: 30px ! important;
        margin-bottom: 40px ! important;
    }
    
    .privacy_prompt_analytics * {
        font-size: 14px ! important;
        line-height: 1.6 ! important;
    }

    .privacy_prompt_analytics .preferences_prompt_submit_analytics,
    .privacy_prompt_analytics .preferences_prompt_unchecked_submit_analytics {
            margin: 20px 10px 0 0px ! important;
    }
    
    .show_more_click_analytics {
        font-size: 14px ! important;
    }
    
    .privacy_prompt_analytics .option_set_analytics {
        -webkit-flex-direction: column ! important;
        flex-direction: column
    }
    
    .privacy_prompt_analytics .show_more_analytics {
        width: 55% ! important;
    }
    
.privacy_prompt_analytics .prompt_click_analytics {
    float: none ! important;
    width: 80% ! important;
    margin: auto ! important;
    display: grid ! important;
}
     .privacy_prompt_title_analytics {
        font-size: 21px ! important;
    }
    
    .privacy_prompt_analytics .show_more_description_analytics ul {
         margin-top: 20px ! important;
    }
    .cookie_banner_checkbox_analytics .checkbox_tick_analytics {
        
    }
}
.vendor_line_container {
    display: flex;
}
.vendor_detail_header {
    font-weight: bold !important;
    font-size: 14px !important;
}
.vendor_title{
    color: #15717D ! important;
    font-weight: bold !important;
    font-size: 14px !important;
}
.vendor_value{
    font-size: 14px !important;
}
details {
    margin-bottom: 5px;
}
details[open] > summary:after {
    content: "-";
}
#show_more_description:not(.is-active) svg{
    display: none;
}
#expand-vendors, #collapse-vendors {
    position: absolute;
    right: 48px;
    cursor: pointer;
}
#collapse-vendors {
    display: none;
}
#expand-vendors svg {
    width: 18px;
    height: 18px;
}
summary {
    outline: none;
    font-size: 1.15em;
    cursor: pointer;
}
summary::-webkit-details-marker {
    display: none
}
summary:after {
    /* background: #da291c; */
    /* border-color: #da291c; */
    /* border-radius: 15px; */
    content: attr(data-more);
    color: #17717d;
    float: left;
    font-size: 0.8em;
    /* font-weight: bold; */
    margin: -2px 10px 0 0;
    padding: 1px 0 3px 0;
    text-align: center;
    width: 80px;
    position: absolute;
    right: 0;
    text-decoration: underline;
    white-space: nowrap;
}

details[open] > summary:after {
    content: attr(data-less);
}

details summary::-webkit-details-marker,
details summary::marker {
 display: none; 
 content: "";
}
.no-data {
    text-align: center;
    color: #E31836 !important;
}

.privacy_prompt_analytics.hide-details{
    overflow-y: unset !important;
}

.cookie_description_analytics li:first-child .cookie_banner_checkbox_analytics {
    cursor: not-allowed !important;
}
/* width */
.privacy_prompt_analytics::-webkit-scrollbar {
  width: 13px;
}

/* Track */
.privacy_prompt_analytics::-webkit-scrollbar-track {
  background: transparent; 
}
 
/* Handle */
.privacy_prompt_analytics::-webkit-scrollbar-thumb {
  background: #bebebe; 
  border-radius: 20px;
}

/* Handle on hover */
.privacy_prompt_analytics::-webkit-scrollbar-thumb:hover {
  background: transparent; 
}
