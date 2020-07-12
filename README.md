# OTRS-Agent-Fullname-at-Header  
- For OTRS CE 6.0.x  
- Display agent fullname at header bar  

1. Modify /opt/otrs/Custom/Kernel/Output/HTML/Template/Standard/Header.tt

			[% RenderBlockEnd("DebugRTLButton") %]
			(+) <font color="red">[% Translate("You are logged in as") | html %] [% Env("UserFullname") | html %]</font>
			</ul>
		</div>
		
  
[![download.png](https://i.postimg.cc/NM766r32/download.png)](https://postimg.cc/vgTxMDHG)  
