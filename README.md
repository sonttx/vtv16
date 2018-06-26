<?xml version="1.0" encoding="UTF-8" standalone="yes"?>
<addons>
    <addon id="lanik.repo" name="Lanik Repository" version="1.0.1" provider-name="Dalibor Lanik">
        <requires>
            <import addon="xbmc.addon" version="12.0.0"/>
        </requires>
        <extension point="xbmc.addon.repository" name="Lanik Repository">
            <info compressed="false">http://kodi.lanik.org/_repo/addons.xml</info>
            <checksum>http://kodi.lanik.org/_repo/addons.xml.md5</checksum>
            <datadir zip="true">http://kodi.lanik.org/_repo/</datadir>
            <hashes>false</hashes>
        </extension>
        <extension point="xbmc.addon.metadata">
            <summary>Repository for my KODI plugins</summary>
            <description>KODI Repository for stuff made by D. Lanik</description>
            <platform>all</platform>
    </extension>
</addon>

<addon id="plugin.audio.hieuhien.vn.itv.music"
       version="1.0.1"
       name="ITV Music"
       provider-name="itv member">
  <requires>
    <import addon="xbmc.python" version="2.1.0" optional="true" />
  </requires>
  <extension point="xbmc.python.pluginsource" library="default.py">
        <provides>audio</provides>
  </extension>
  <extension point="xbmc.addon.metadata">
    <summary>Entertainment</summary>
    <description>Nghe nhạc online</description>
	<disclaimer lang="en">Nguồn data trên web nên chúng tôi không chịu trách nhiệm về sự ổn định.</disclaimer>
    <platform>all</platform>
  </extension>
</addon>

<addon id="plugin.audio.hieuhien.vn.itv.nhacso"
       name="Nhạc Số"
       version="1.0.1"
       provider-name="itv member">
	<requires>
		<import addon="xbmc.python" version="2.1.0" />
		<import addon="script.module.simple.downloader" version="1.9.4" />
	</requires>
  	<extension point="xbmc.python.pluginsource" library="default.py" >
  		<provides>audio</provides>
 	 </extension>
  	<extension point="xbmc.addon.metadata">
		<summary lang="en">Entertainment</summary>
		<description lang="en">Thử nghiệm nghe nhạc tại http://nhacso.net/</description>
        <disclaimer lang="en">Nguồn data trên web nên chúng tôi không chịu trách nhiệm về sự ổn định.</disclaimer>
        <platform>all</platform>
        <language>en</language>
    </extension>
</addon>

<addon id="plugin.audio.hieuhien.vn.vietmusic"
       version="1.8.3"
       name="VietMusic"
       provider-name="VietMusic">
  <requires>
    <import addon="xbmc.python" version="2.1.0" optional="true" />
	<import addon="script.module.simple.downloader" version="1.9.4" />
	<import addon="script.module.t0mm0.common" version="1.1.0"/>
  </requires>
  <extension point="xbmc.python.pluginsource" library="default.py">
        <provides>audio</provides>
  </extension>
  <extension point="xbmc.addon.metadata">
    <summary>Viet Music online</summary>
    <description>Add-on play Vietnamese Music online</description>
    <platform>all</platform>
  </extension>
</addon>

<addon id="plugin.audio.hieuhien.vn.xsharefree" name="[COLOR lime][B]Xshare [/COLOR][COLOR red]Music[/COLOR] [COLOR blue]Center[/B][/COLOR]" version="3.4.5.1" provider-name="thaitni">
    <requires>
        <import addon="xbmc.python" version="2.1.0" optional="true" />
    </requires>
    <extension point="xbmc.python.pluginsource" library="xshare.py">
        <provides>audio</provides>
    </extension>
    <extension point="xbmc.addon.metadata">
        <summary>Xshare - XBMC HD Video</summary>
		<description lang="en">Tìm và nghe nhạc trên XBMC từ: chiasenhac.com, nhaccuatui.com va nhacdj.vn</description>
		<platform>all</platform>
		<language>en</language>
		<license>GNU General Public License - v2</license>
		<source>https://github.com/thaitni/xbmc.repo.xshare</source>
		<email>thai@thanhthai.net</email>
    </extension>
</addon>

<addon id="plugin.program.gdrive" version="0.7.6" name="gdrive" provider-name="ddurdle">
    <requires>
        <import addon="xbmc.python" version="2.1.0"/>
    </requires>
    <extension point="xbmc.python.pluginsource" library="default.py">
        <provides>executable</provides>
    </extension>
    <extension point="xbmc.addon.metadata">
        <summary>Listen to music, watch videos and view photos from your Google Drive account</summary>
        <description>Plays music and video from your Google Drive account.  Not affiliated with Google.</description>
        <platform>all</platform>
    </extension>
</addon>

<addon id="plugin.program.hieuhien.vn.FelvsWizard" name="Felvs Wizard" version="2.0.8.1" provider-name="Felv">
  <requires>
    <import addon="xbmc.python" version="2.1.0"/>
  </requires>
  <extension point="xbmc.python.pluginsource" library="default.py">
        <provides></provides>
  </extension>
  <extension point="xbmc.addon.metadata">
    <summary lang="en">Felvs Wizard</summary>
    <description lang="en">Felvs Wizard allows you to get access to the latest Custom Builds.</description>
    <platform>all</platform>
  </extension>
</addon>

<addon id="plugin.video.castaway" name="Castaway" version="0.2.6" provider-name="natko1412">
	<requires>
		<import addon="xbmc.python" version="2.1.0"/>
		<import addon="script.module.beautifulsoup" version="3.2.1"/>
		<import addon="script.module.requests"  />
    	<import addon="script.module.addon.common" />
		<import addon="script.module.urlresolver" />
		<import addon="script.module.liveresolver"  />

	</requires>
	<extension point="xbmc.python.pluginsource" library="default.py">
		<provides>video</provides>
	</extension>
	<extension point="xbmc.addon.metadata">
		<summary lang="en">Just a castaway.</summary>
		<description lang="en">Visit TVADDONS.ag for support.
		</description>
		<disclaimer lang="en">The author does not host or distribute any of the content displayed by this addon. The author does not have any affiliation with the content provider.</disclaimer>

		<platform>all</platform>
	</extension>
</addon>

<addon id="plugin.video.f4mTester" version="2.6.2" name="f4mTester" provider-name="Shani">
    <requires>
        <import addon="xbmc.python" version="2.1.0"/>
        <import addon="script.video.F4mProxy" version="2.6.2"/>
    </requires>
    <extension point="xbmc.python.pluginsource" library="default.py">
        <provides>video</provides>
    </extension>
    <extension point="xbmc.addon.metadata">
        <summary>f4mTester</summary>
        <description></description>
        <platform>all</platform>
    </extension>
</addon>

<addon
  id="plugin.video.HieuHien.vn"
  version="1.0.2"
  name="[B][COLOR lime]Trung tâm giải trí[/COLOR][/B]"
  provider-name="thongld">
  <requires>
    <import addon="xbmc.python" version="2.1.0"/>
    <import addon="script.module.xbmcswift2" version="0.0.7" />
    <import addon="plugin.video.youtube" version="4.4.1" />
    <import addon="script.module.httplib2" version="0.1" />
  </requires>
  <extension point="xbmc.python.pluginsource" library="default.py">
        <provides>video</provides>
  </extension>
  <extension point="xbmc.addon.metadata">
    <summary>Hieuhien.vn Media Center cho người Việt</summary>
    <description>Trung tâm giải trí - tất cả trong 1 cho người Việt - Addon này được chỉnh sửa nội dung từ addon [COLOR yellow]VN Open Playlist[/COLOR] của tác giả [COLOR blue]thongld[/COLOR] - Xin cảm ơn tác giả đã cho phép [COLOR red]HieuHien.vn[/COLOR] chỉnh sửa để sử dụng theo cách riêng của mình!</description>
    <platform>all</platform>
  </extension>
</addon>

<addon id="plugin.video.hieuhien.vn.anhtrang.org" name="[COLOR lime][B]Phim AnhTrang.org[/B][/COLOR]" provider-name="thongld" version="1.0.5">
  <requires>
    <import addon="xbmc.python" version="2.1.0" />
    <import addon="script.module.xbmcswift2" version="1.3.1" />
    <import addon="plugin.video.youtube" version="4.4.1" />
  </requires>
  <extension library="default.py" point="xbmc.python.pluginsource">
    <provides></provides>
  </extension>
  <extension point="xbmc.addon.metadata">
    <platform>all</platform>
    <summary>Watch free movies from anhtrang.org</summary>
    <description>Watch free movies from anhtrang.org</description>
  </extension>
</addon>

<addon
  id="plugin.video.hieuhien.vn.azdrama"
  version="1.0.29"
  name="azdrama.net"
  provider-name="Dknight (maintained by cthlo)">
  <requires>
        <import addon="xbmc.python" version="2.1.0" optional="true" />
		<import addon="script.module.html5lib" version="0.999.0"/>
		<import addon="script.module.beautifulsoup4" version="4.3.2"/>
		<import addon="script.module.simplejson" />
		<import addon="script.module.t0mm0.common" version="1.1.0"/>
    <import addon="script.module.urlresolver" version="2.10.11"/>
  </requires>
  <extension point="xbmc.python.pluginsource"
            library="default.py">
        <provides></provides>
  </extension>
  <extension point="xbmc.addon.metadata">
    <summary>azdrama.net</summary>
    <description>Watch azdrama.net (Chinese)Videos</description>
    <platform>all</platform>
  </extension>
</addon>

<addon id="plugin.video.hieuhien.vn.ccloudtv" name="cCloud TV" version="1.4.2" provider-name="podgod">
  <requires>
    <import addon="xbmc.python" version="2.1.0"/>
    <import addon="script.module.beautifulsoup" version="3.2.1"/>
    <import addon="script.module.simple.downloader" version="0.9.4"/>
    <import addon="script.module.beautifulsoup4"/>
    <import addon="script.module.simple.downloader" version="0.9.4"/>
    <import addon="script.module.requests"/>
    <import addon="script.module.httplib2"/>
    <import addon="script.module.youtube.dl" optional="true"/>
    <import addon="plugin.video.youtube"/>
    <import addon="script.module.urlresolver" optional="true"/>
    <import addon="script.module.simplejson"/>
  </requires>
  <extension point="xbmc.python.pluginsource" library="default.py">
    <provides>video</provides>
  </extension>
  <extension point="xbmc.addon.metadata">
    <summary>All the best from cCloud TV</summary>
    <description>cCloud is an open source cloud based social IPTV service. It is built by the community for the community, where streaming is just a click away. Just click, play and stream yup it's that simple. Just go to http://ccloudtv.org  and enjoy:) Please report any channels that are down here http://www.tiny.cc/reportchs
    </description>
	<license>http://www.gnu.org/licenses/</license>
    <forum>http://ccloudtv.org/forum</forum>
    <website>http://ccloudtv.org</website>
    <website>http://facebook.com/ccloudapp</website>
    <website>http://twitter.com/ccloudapp</website>
    <email/>
    <platform>all</platform>
  </extension>
</addon>

<addon
	id="plugin.video.hieuhien.vn.chantube"
	version="1.0.3"
	name="[COLOR violet][B]ChanTube[/B][/COLOR]"
	provider-name="chanmodoi">
	<requires>
		<import addon="xbmc.python" version="2.1.0" />
	</requires>
	<extension point="xbmc.python.pluginsource" library="addon.py">
		<provides></provides>
	</extension>
	<extension point="xbmc.addon.metadata">
	<summary>ChanTube</summary>
	<description>Tổng hợp các kênh Youtube hay</description>
	<platform>all</platform>
</extension>
</addon>

<addon
  id="plugin.video.hieuhien.vn.drama24h"
  version="1.0.9"
  name="drama24h"
  provider-name="Dknight">
  <requires>
        <import addon="xbmc.python" version="2.1.0" optional="true" />
		<import addon="script.module.beautifulsoup" version="3.0.8"/>
		<import addon="script.module.urlresolver" version="2.1.2"/>
		<import addon="script.module.simplejson" />
		<import addon="script.module.t0mm0.common" version="1.1.0"/>
  </requires>
  <extension point="xbmc.python.pluginsource"
            library="default.py">
        <provides></provides>
  </extension>
  <extension point="xbmc.addon.metadata">
    <summary>drama24h</summary>
    <description>Watch drama24h (Chinese)Videos</description>
    <platform>all</platform>
  </extension>
</addon>

<addon
  id="plugin.video.hieuhien.vn.dramago"
  version="1.0.10"
  name="DramaGo"
  provider-name="Dknight">
  <requires>
        <import addon="xbmc.python" version="2.1.0" optional="true" />
		<import addon="script.module.simplejson" />
		<import addon="script.module.beautifulsoup" version="3.0.8"/>
		<import addon="script.module.urlresolver"  version="0.0.1"/>
		<import addon="script.module.t0mm0.common" version="1.1.0"/>
  </requires>
  <extension point="xbmc.python.pluginsource"
            library="default.py">
        <provides></provides>
  </extension>
  <extension point="xbmc.addon.metadata">
    <summary>DramaGo</summary>
    <description>Watch Asain Drama Movies and TVShows on DramaGo</description>
    <platform>all</platform>
  </extension>
</addon>

<addon id="plugin.video.hieuhien.vn.exodus" version="1.3.7" name="Exodus" provider-name="Exodus">
	<requires>
		<import addon="xbmc.python" version="2.19.0" />
		<import addon="repository.exodus" version="1.0.0" />
		<import addon="script.exodus.artwork" version="1.0.1" />
		<import addon="script.module.urlresolver" version="3.0.0"/>
		<import addon="script.module.metahandler" version="1.0.0" />
		<import addon="plugin.video.youtube" version="5.2.1" optional="true" />
	</requires>
	<extension point="xbmc.python.pluginsource" library="default.py">
		<provides></provides>
	</extension>
	<extension point="xbmc.addon.metadata">
		<summary lang="en">Exodus</summary>
		<description lang="en">Please visit www.tvaddons.ag for Exodus support and assistance! Kindly note that Exodus is not an official part of the media player you are running, and therefore not to be mentioned within official support channels, this addon has nothing to do with the media player itself, nor it’s intended use, it is simply a third party plugin which has been added to your system.</description>
		<disclaimer lang="en">The author does not host or distribute any of the content displayed by this addon. The author does not have any affiliation with the content provider.</disclaimer>
		<platform>all</platform>
	</extension>
</addon>

<addon id="plugin.video.hieuhien.vn.footballreplays" name="[COLOR violet]Bóng đá xem lại[/COLOR]" version="3.0.3" provider-name=".[COLOR blue]X[/COLOR]unity[COLOR blue]T[/COLOR]alk">
	<requires>
		<import addon="xbmc.python" version="2.1.0"/>
    <import addon="script.module.urlresolver" version="0.0.1"/>
	</requires>
	<extension point="xbmc.python.pluginsource" library="default.py">
		<provides></provides>
	</extension>
	<extension point="xbmc.addon.metadata">
		<summary lang="en">Football Replays</summary>
		<description lang="en">Football Replays</description>
		<disclaimer lang="en">By using This Plugin You will receive sometimes an advert which helps funds the developers developing.....we all thank you!!</disclaimer>
		<platform>all</platform>
	</extension>
</addon>

<addon
	id="plugin.video.hieuhien.vn.hayhaytv"
	version="1.0.6"
	name="[B]HayHayTV[B]"
	provider-name="lnt900">
	<requires>
		<import addon="xbmc.python" version="2.1.0"/>
	</requires>
	<extension point="xbmc.python.pluginsource" library="default.py">
	<provides></provides>
	</extension>
	<extension point="xbmc.addon.metadata">
	<summary>hayhaytv</summary>
	<description>Watch hayhaytv.vn (Vietnamese) Videos</description>
	<platform>all</platform>
	</extension>
</addon>

<addon id="plugin.video.hieuhien.vn.hdonline" name="HDOnline" version="1.0.6" provider-name="anhlon">
	<requires>
		<import addon="xbmc.python" version="2.1.0"/>
		<import addon="script.module.framework" version="1.4"/>
	</requires>
	<extension point="xbmc.python.pluginsource" library="default.py">
		<provides></provides>
	</extension>
	<extension point="xbmc.addon.metadata">
		<summary lang="en"></summary>
		<description lang="en"></description>
		<disclaimer lang="en"></disclaimer>
		<platform>all</platform>
	</extension>
</addon>

<addon
	id="plugin.video.hieuhien.vn.hdviet"
	version="1.1.10"
	name="[B]HDViet[/B]"
	provider-name="lnt900">
	<requires>
		<import addon="xbmc.python" version="2.1.0"/>
	</requires>
	<extension point="xbmc.python.pluginsource" library="default.py">
		<provides></provides>
	</extension>
	<extension point="xbmc.addon.metadata">
	<summary>HDViet</summary>
	<description>Watch free videos from hdviet.com</description>
	<platform>all</platform>
	</extension>
</addon>

<addon id="plugin.video.hieuhien.vn.hdvietsd" name="[B]HDViet SD[/B]" version="1.0.1" provider-name="">
	<requires>
		<import addon="xbmc.python" version="2.1.0"/>
		<import addon="script.module.simplejson" optional="true"/>
		<import addon="script.common.plugin.cache" version="2.5.5"/>
	</requires>
	<extension point="xbmc.python.pluginsource" library="default.py">
		<provides></provides>
	</extension>
	<extension point="xbmc.addon.metadata">
		<summary lang="en"></summary>
		<description lang="en"></description>
		<disclaimer lang="en"></disclaimer>
		<platform>all</platform>
	</extension>
</addon>

<addon
	id="plugin.video.hieuhien.vn.htvonline"
	version="1.0.6"
	name="[COLOR violet][B]HTV Online[/B][/COLOR]"
	provider-name="thongld">
	<requires>
		<import addon="xbmc.python" version="2.1.0"/>
	</requires>
	<extension point="xbmc.python.pluginsource" library="default.py">
	<provides></provides>
	</extension>
	<extension point="xbmc.addon.metadata">
	<summary>HTV Online</summary>
	<description>Watch free HTVOnline.com.vn (Vietnamese) Channels</description>
	<platform>all</platform>
	</extension>
</addon>

<addon id="plugin.video.hieuhien.vn.itvplus"
       version="2.4.3"
       name="[COLOR ffff0000]*ITV*[/COLOR]Plus"
       provider-name="itv member">
    <requires>
        <import addon="xbmc.python" version="2.1.0" optional="true" />
	    <import addon="script.module.simplejson" />
	    <import addon="script.module.t0mm0.common" />
    </requires>
    <extension point="xbmc.python.pluginsource" library="default.py">
		<provides></provides>
	</extension>
    <extension point="xbmc.service" library="autorun.py" start="startup">
    </extension>
    <extension point="xbmc.addon.metadata">
        <summary>ITV Entertainment</summary>
        <description>
* Addon được ITVPlus xây dựng dựa vào nguồn dữ liệu trên internet. Bản quyền tác giả thuộc về ITVPlus.
* Với mục đích phục vụ nhu cầu giải trí cho cộng đồng Kodi. Chúng tôi đã tốn nhiều thời gian và công sức để tạo ra sản phẩm, vì vậy mong các tổ chức và cá nhân tuân thủ các quy định sau:
- Không tự ý sử dụng mã nguồn của addon khi chưa có sự đồng ý của nhóm lập trình viên ITVPlus.
- Không tự ý chỉnh sửa lại addon và chia sẻ, quảng cáo phục vụ cho nhu cầu lợi ích của một cá nhân hay tập thể nào đó.
	    </description>
	    <disclaimer lang="en">[COLOR ffff0000]Data được chia sẻ trên internet. Chúng tôi không chịu mọi trách nhiệm pháp lý.[/COLOR]</disclaimer>
        <platform>all</platform>
    </extension>
</addon>

<addon id="plugin.video.hieuhien.vn.kenh108.com" name="[COLOR lime][B]kenh108.com[/B][/COLOR]" provider-name="thongld" version="1.0.3">
  <requires>
    <import addon="xbmc.python" version="2.1.0" />
    <import addon="script.module.xbmcswift2" version="1.3.1" />
    <import addon="plugin.video.youtube" version="4.4.1" />
  </requires>
  <extension library="default.py" point="xbmc.python.pluginsource">
    <provides></provides>
  </extension>
  <extension point="xbmc.addon.metadata">
    <platform>all</platform>
    <summary>Watch free movies from kenh108.com</summary>
    <description>Watch free movies from kenh108.com</description>
  </extension>
</addon>

<addon
  id="plugin.video.hieuhien.vn.kenh88"
  version="1.0.0"
  name="[COLOR lime][B]Kênh 88[/B][/COLOR]"
  provider-name="Dknight">
  <requires>
        <import addon="xbmc.python" version="2.1.0" optional="true" />
		<import addon="script.module.beautifulsoup" version="3.0.8"/>
		<import addon="script.module.simplejson" />
		<import addon="script.module.t0mm0.common" version="1.1.0"/>
  </requires>
  <extension point="xbmc.python.pluginsource"
            library="default.py">
        <provides></provides>
  </extension>
  <extension point="xbmc.addon.metadata">
    <summary>kenh88</summary>
    <description>Watch kenh88.com(Vietnamese)Videos</description>
    <platform>all</platform>
  </extension>
</addon>

<addon id="plugin.video.hieuhien.vn.liveshow"
       name="[COLOR lime][B]Show Tổng Hợp[/B][/COLOR]"
       version="1.0.0"
       provider-name="HopDenTV">
  <requires>
    <import addon="xbmc.python" version="2.1.0"/>
    <import addon="script.module.beautifulsoup" version="3.2.1"/>
    <import addon="script.module.simple.downloader" version="0.9.4"/>
    <import addon="script.module.simplejson" />
  </requires>
  <extension point="xbmc.python.pluginsource" library="default.py">
    <provides></provides>
  </extension>
  <extension point="xbmc.addon.metadata">
    <summary>Liveshow tổng hợp</summary>
    <description>Addon này dược viết lại từ addon "Chương trình đặc biệt" của tác giả HopDenTV </description>
    <platform>all</platform>
  </extension>
</addon>

<addon id="plugin.video.hieuhien.vn.livestream"
       name="[B][COLOR white]Live Stream [COLOR orange]PRO[/COLOR][/COLOR][/B]"
       version="2.7.2"
       provider-name="Shani">
  <requires>
    <import addon="xbmc.python" version="2.1.0"/>
    <import addon="script.module.beautifulsoup" version="3.2.1"/>
    <import addon="script.module.simple.downloader" version="0.9.4"/>
    <import addon="script.module.beautifulsoup4" />
    <import addon="script.module.requests" />
    <import addon="script.module.httplib2" />
    <import addon="script.module.liveresolver" version="0.1.24" optional="true"/>
    <import addon="script.module.youtube.dl" optional="true"/>
    <import addon="plugin.video.youtube" optional="true" />
    <import addon="script.module.urlresolver" optional="true"/>
    <import addon="script.module.simplejson" />
     <import addon="script.module.livestreamer" optional="true"/>
     <import addon="script.module.pyamf" optional="true"/>
  </requires>
  <extension point="xbmc.python.pluginsource" library="default.py">
    <provides>video</provides>
  </extension>


  <extension point="xbmc.addon.metadata">
    <summary>livestreamspro- shamelessly forked from livestreams but added many thinks</summary>
    <description>
        In addition to what livestreams allowed you to do, you can now,
        1. call regex in regex,
        2. multiple regex in page, regex in session, also htmlunescape responses
        3. create session from one regex and pass onto next in line
        4. save sessions to a file and open again later
        5. write python code in .py file, put in the profile directory and then call from your regex.
        6. use epoctime, guid and unpack as functions already defined.
        7. Use it to post values to the pages to get the proper responses
        8. support many headers, like origin, X-Requested-With
        9. you can now append cookies in response and then read in regex using includeheaders
        10. You can now link to another web url via your xml using externallink
        11. support for google captcha, now you can show and then post the text

    </description>
    <platform>all</platform>
  </extension>
</addon>

<addon id="plugin.video.hieuhien.vn.megabox" name="[B]Cantobu Media[/B]" version="2.1.10.3" provider-name="phuoclv">
    <requires>
        <import addon="xbmc.python" version="2.1.0" optional="true" />
		<import addon="script.module.simplejson" />
		<import addon="script.module.simple.downloader" version="1.9.4" />
	</requires>
    <extension point="xbmc.python.pluginsource" library="default.py">
        <provides></provides>
    </extension>
    <extension point="xbmc.service" library="autorun.py" start="startup"></extension>
    <extension point="xbmc.addon.metadata">
        <summary>Cantobu Media Entertainment</summary>
		<description>Giải trí trên XBMC/Kodi được viết lại dựa trên addon ITV Plus của tác giả itv member, XShare (thaitni), VietMedia (tinhyeu44), ...</description>
		<disclaimer>Tất cả nội dung được lấy từ Internet - Tôi hoàn toàn không chịu trách nhiệm về bản quyền hay độ ổn định của chương trình</disclaimer>
		<source>https://github.com/phuoclv/repository.cantobumedia</source>
		<platform>all</platform>
    </extension>
</addon>

<addon
	id="plugin.video.hieuhien.vn.megafun.vn"
	version="1.0.19"
	name="[COLOR violet][B]Truyền hình Xem lại[/B][/COLOR]"
	provider-name="ThongLD">
	<requires>
		<import addon="xbmc.python" version="2.1.0"/>
	</requires>
	<extension point="xbmc.python.pluginsource" library="default.py">
		<provides></provides>
	</extension>
	<extension point="xbmc.addon.metadata">
		<summary>Megafun.VN</summary>
		<description>[COLOR lime][B]Addon xem lại một số kênh truyền hình[/B][/COLOR]</description>
		<platform>all</platform>
	</extension>
</addon>

<addon id="plugin.video.hieuhien.vn.moviebox" name="[COLOR lime]Phim MovieBox[/COLOR]" provider-name="thongld" version="0.5">
  <requires>
    <import addon="xbmc.python" version="2.1.0" />
    <import addon="script.module.xbmcswift2" version="1.3.1" />
    <import addon="plugin.video.youtube" version="4.4.1" />
  </requires>
  <extension library="default.py" point="xbmc.python.pluginsource">
    <provides></provides>
  </extension>
  <extension point="xbmc.addon.metadata">
    <platform>all</platform>
    <summary>Unofficial Kodi addon of MovieBox Android app</summary>
    <description>Unofficial Kodi addon of MovieBox Android app</description>
  </extension>
</addon>

<addon id="plugin.video.hieuhien.vn.movihd" name="[B]MoviHD[/B]" version="1.0.4" provider-name="anhlon">
	<requires>
		<import addon="xbmc.python" version="2.7.0"/>
		<import addon="script.module.framework" version="1.4"/>
	</requires>
	<extension point="xbmc.python.pluginsource" library="default.py">
		<provides></provides>
	</extension>
	<extension point="xbmc.addon.metadata">
		<summary lang="en"></summary>
		<description lang="en"></description>
		<disclaimer lang="en"></disclaimer>
		<platform>all</platform>
	</extension>
</addon>

<addon id="plugin.video.hieuhien.vn.muchmovies.hd" name="[COLOR yellow][B]Much Movies HD[/B][/COLOR]" version="1.7.5" provider-name="lambda">
	<requires>
		<import addon="xbmc.python" version="2.1.0"/>
		<import addon="script.module.metahandler" version="1.0.0"/>
		<import addon="script.common.plugin.cache" version="0.9.1"/>
		<import addon="script.module.simplejson" optional="true"/>
		<import addon="script.module.parsedom" optional="true"/>
		<import addon="plugin.video.youtube" optional="true"/>
	</requires>
	<extension point="xbmc.python.pluginsource" library="default.py">
		<provides></provides>
	</extension>
	<extension point="xbmc.addon.metadata">
		<summary lang="en">Watch a wide selection of movies from muchmovies.org</summary>
		<description lang="en">Visit TVADDONS.ag for support</description>
		<disclaimer lang="en">The author does not host or distribute any of the content displayed by this addon. The author does not have any affiliation with the content provider.</disclaimer>
		<forum>http://forums.tvaddons.ag/forums/148-lambda-s-xbmc-addons</forum>
		<source>https://offshoregit.com/lambda81/</source>
		<website>https://offshoregit.com/lambda81/</website>
		<platform>all</platform>
	</extension>
</addon>

	<addon id="plugin.video.hieuhien.vn.myasiantv" version="1.1" name="[COLOR yellow][B]MyAsianTV.se[/B][/COLOR]" provider-name="V137">
		<requires>
			<import addon="xbmc.python" version="2.1.0"/>
		</requires>
		<extension point="xbmc.python.pluginsource" library="default.py">
			<provides></provides>
		</extension>
		<extension point="xbmc.addon.metadata">
			<summary>MyAsianTV.se</summary>
			<description>MyAsianTV.se</description>
			<platform>all</platform>
		</extension>
	</addon>

<addon id="plugin.video.hieuhien.vn.p2psport"
	name="[COLOR violet][B]Bóng đá P2P Sport[/B][/COLOR]"
	version="0.1.0"
	provider-name="natko1412">
  <requires>
    <import addon="xbmc.python" version="2.1.0"/>
    <import addon="program.plexus" />
    <import addon="script.module.addon.common" version="2.0.0" />
    <import addon="script.module.requests" />
    <import addon="script.module.beautifulsoup" version="3.2.1"/>
    <import addon="script.module.mechanize" version="0.2.6"/>

  </requires>
  <extension point="xbmc.python.pluginsource" library="default.py">
    <provides>video</provides>
  </extension>
  <extension point="xbmc.addon.metadata">
    <summary>Watch p2p sports in Kodi</summary>

    <platform>all</platform>
    <forum>forums.tvaddons.ag</forum>

  </extension>
</addon>

<addon id="plugin.video.hieuhien.vn.p2pstreams"
       name="[COLOR violet][B]Bóng đá P2P-Streams[/B][/COLOR]"
       version="1.4.1"
       provider-name="enen92,fightnight">
  <requires>
    <import addon="xbmc.python" version="2.1.0"/>
    <import addon="script.module.beautifulsoup" version="3.0.8"/>
    <import addon="script.module.simplejson" />
    <import addon="script.module.pytz" />
    <import addon="script.module.requests" />
    <import addon="script.module.mechanize" version="0.2.6"/>
  </requires>
  <extension point="xbmc.python.pluginsource"
            library="default.py" />
  <extension point="xbmc.service" library="server.py" start="startup" />
  <extension point="xbmc.addon.metadata">
    <summary>SopCast and AceStream</summary>
    <description lang="en">AceStream and Sopcast in your favourite media center! Watch peer-to-peer streams in Kodi without the need for external players. Project page: https://github.com/enen92/P2P-Streams-Kodi</description>
    <description lang="pt">AceStream e Sopcast no seu Media-Center de eleição! Assista a streams peer-to-peer no Kodi sem a necessidade de players externos. Página do projecto: https://github.com/enen92/P2P-Streams-Kodi</description>
    <description lang="nl">Acestream en Sopcast in jouw favoriete media center. Kijk peer-to-peer streams in Kodi zonder de noodzaak voor externe spelers. Project pagina: https://github.com/enen92/P2P-Streams-Kodi/</description>
    <description lang="it">AceStream e SopCast nel tuo Media Center preferito! Guarda i canali peer-to-peer in Kodi senza la necessità di player esterni. Pagina del progetto: https://github.com/enen92/P2P-Streams-Kodi/</description>
    <disclaimer lang="en">The authors does not host nor distribute any of the content you may watch using this addon. The authors have no affiliation with any of the content providers. This addon does not track its users.</disclaimer>
    <disclaimer lang="pt">Os autores não alojam nem distribuem nenhum do conteúdo acessível a partir deste addon. Os autores não têm qualquer afiliação com nenhum dos sites utilizados por este addon. O addon não contem nenhuma ferramenta de tracking.</disclaimer>
    <disclaimer lang="nl">De auteurs houden of delen niets van de inhoud die u kunt bekijken met behulp van deze addon. De auteurs hebben geen banden met welke leverancier van inhoud dan ook. Deze addon houdt geen gegevens bij van zijn gebruikers.</disclaimer>
    <disclaimer lang="it">L'autore non detiene o distribuisce alcun contenuto fruibile tramite l'utilizzo di questo addon. L'autore non è affiliato con nessun fornitore dei contenuti. Questo addon non traccia i suoi utenti.</disclaimer>
    <forum>http://forum.kodi.tv/showthread.php?tid=201894</forum>
    <source>https://github.com/enen92/P2P-Streams-Kodi | https://github.com/enen92/P2P-Streams-Kodi--Modules-</source>
    <website>https://code.google.com/p/p2p-strm/</website>
    <platform>all</platform>
  </extension>
</addon>

<addon
	id="plugin.video.hieuhien.vn.phatam"
	version="1.0.2"
	name="[COLOR yellow][B]Phật Âm[/B][/COLOR]"
	provider-name="traitravinh">
	<requires>
	</requires>
	<extension point="xbmc.python.pluginsource" library="phatam.py">
		<provides></provides>
	</extension>
	<extension point="xbmc.addon.metadata">
	<summary>Watch KinhPhat</summary>
	<description>A-Di-Da-Phat</description>
	<platform>all</platform>
	</extension>
</addon>

	<addon id="plugin.video.hieuhien.vn.phim14.net" version="2.2" name="[B]Phim14.net[/B]" provider-name="V137">
		<requires>
			<import addon="xbmc.python" version="2.1.0" />
			<import addon="script.module.requests" version="2.6.0"/>
			<import addon="script.module.urlresolver" version="1.0.0"/>
			<import addon="script.module.xbmcswift2" version="1.3.1" />
			<import addon="script.module.t0mm0.common" version="1.1.0"/>
		</requires>
		<extension library="default.py" point="xbmc.python.pluginsource">
			<provides></provides>
		</extension>
   		<extension point="xbmc.addon.metadata">
			<summary>Phim14.net</summary>
			<description>Phim14.net (Vietnamese)</description>
			<platform>all</platform>
		</extension>
	</addon>

<addon id="plugin.video.hieuhien.vn.phim3s" name="[B]Phim3s[/B]" version="1.3.8" provider-name="anhlon">
	<requires>
		<import addon="xbmc.python" version="2.7.0"/>
		<import addon="script.module.framework" version="1.4"/>
	</requires>
	<extension point="xbmc.python.pluginsource" library="default.py">
		<provides></provides>
	</extension>
	<extension point="xbmc.addon.metadata">
		<summary lang="en"></summary>
		<description lang="en"></description>
		<disclaimer lang="en"></disclaimer>
		<platform>all</platform>
	</extension>
</addon>

<addon
  id="plugin.video.hieuhien.vn.phim60s"
  version="2.0.12"
  name="[COLOR lime][B]Phim60s[/B][/COLOR]"
  provider-name="thongld">
  <requires>
    <import addon="xbmc.python" version="2.1.0"/>
    <import addon="script.module.xbmcswift2" version="1.3.1" />
    <import addon="plugin.video.youtube" version="4.4.1" />
  </requires>
  <extension point="xbmc.python.pluginsource" library="default.py">
        <provides></provides>
  </extension>
  <extension point="xbmc.addon.metadata">
    <summary>phim60s</summary>
    <description>Watch free phim60s.info (Vietnamese) Videos</description>
    <platform>all</platform>
  </extension>
</addon>

<addon
	id="plugin.video.hieuhien.vn.phimanhtrang"
	version="1.0.1"
	name="[B]Phim Ánh Trăng[/B]"
	provider-name="DaveLN">
	<requires>
		<import addon="xbmc.python" version="2.1.0" optional="true" />
		<import addon="script.module.simplejson" />
		<import addon="script.module.t0mm0.common" version="1.1.0"/>
	</requires>
	<extension point="xbmc.python.pluginsource" library="default.py">
		<provides></provides>
	</extension>
	<extension point="xbmc.addon.metadata">
		<summary>Movies</summary>
		<description>[COLOR lime][B]Xem phim từ website anhtrang.org[/B][/COLOR]</description>
		<disclaimer lang="en">
			[COLOR lime]The streaming media are pulled from online provider(s).
			[COLOR red]These streams do not represent my views or opinions in any way.[/COLOR]</disclaimer>
		<platform>all</platform>
		<license>http://www.gnu.org/licenses/</license>
		<forum></forum>
		<website></website>
		<email></email>
		<source></source>
	</extension>
</addon>

	<addon id="plugin.video.hieuhien.vn.phimlt"  version="1.9" name="[COLOR lime][B]PhimLT.com[/B][/COLOR]" provider-name="V137">
		<requires>
			<import addon="xbmc.python" version="2.1.0" />
			<import addon="script.module.xbmcswift2" version="1.3.1" />
			<import addon="plugin.video.youtube" version="4.4.1" />
			<import addon="script.module.requests" version="2.6.0"/>
		</requires>
		<extension library="default.py" point="xbmc.python.pluginsource">
			<provides></provides>
		</extension>
		<extension point="xbmc.addon.metadata">
			<summary>PhimLT.com</summary>
			<description>PhimLT.com (Vietnamese)</description>
			<platform>all</platform>
		</extension>
	</addon>

	<addon id="plugin.video.hieuhien.vn.phimmedia" version="1" name="Phim.Media" provider-name="V137">
		<requires>
			<import addon="xbmc.python" version="2.1.0" />
			<import addon="script.module.beautifulsoup4" version="4.3.2" />
			<import addon="script.module.pil" version="1.1.7" />
			<import addon="script.module.requests" version="2.6.0" />
			<import addon="script.module.six" version="1.0.0" />
		</requires>
		<extension point="xbmc.python.pluginsource" library="default.py">
			<provides></provides>
		</extension>
		<extension point="xbmc.addon.metadata">
			<summary>Phim.Media</summary>
			<description>Phim.Media (Vietnamese)</description>
			<platform>all</platform>
		</extension>
	</addon>

<addon id="plugin.video.hieuhien.vn.phimmoi" name="[B]PhimMoi.net[/B]" version="1.3.8" provider-name="anhlon">
	<requires>
		<import addon="xbmc.python" version="2.7.0"/>
		<import addon="script.module.framework" version="1.4"/>
	</requires>
	<extension point="xbmc.python.pluginsource" library="default.py">
		<provides></provides>
	</extension>
	<extension point="xbmc.addon.metadata">
		<summary lang="en"></summary>
		<description lang="en"></description>
		<disclaimer lang="en"></disclaimer>
		<platform>all</platform>
	</extension>
</addon>

	<addon id="plugin.video.hieuhien.vn.phimnhanh" version="1.1" name="[COLOR lime][B]PhimNhanh.com[/B][/COLOR]" provider-name="V137">
		<requires>
			<import addon="xbmc.python" version="2.1.0"/>
			<import addon="script.module.requests" version="2.6.0"/>
		</requires>
		<extension point="xbmc.python.pluginsource" library="default.py">
			<provides></provides>
		</extension>
		<extension point="xbmc.addon.metadata">
			<summary>PhimNhanh.com</summary>
			<description>PhimNhanh.com (Vietnamese)</description>
			<platform>all</platform>
		</extension>
	</addon>

<addon
  id="plugin.video.hieuhien.vn.phimvang"
  version="1.0.0"
  name="[COLOR lime][B]Phim Vàng[/B][/COLOR]"
  provider-name="traitravinh">
  <requires>
    <import addon="xbmc.python" version="2.1.0" optional="true"/>
    <import addon="script.module.requests" version="2.4.3" />
  </requires>
  <extension point="xbmc.python.pluginsource"
            library="phimvang.py">
        <provides></provides>
  </extension>
  <extension point="xbmc.addon.metadata">
    <summary>Watch Movies</summary>
    <description>Watch Movies on phimvang.com</description>
    <platform>all</platform>
  </extension>
</addon>

<addon
  id="plugin.video.hieuhien.vn.sctv"
  version="3.0.3.1"
  name="SCTV"
  provider-name="thong.ld">
  <requires>
    <import addon="xbmc.python" version="2.1.0"/>
    <import addon="script.module.xbmcswift2" version="1.3.1" />
    <import addon="script.module.requests" version="1.0" />
  </requires>
  <extension library="default.py" point="xbmc.python.pluginsource">
    <provides></provides>
  </extension>
  <extension point="xbmc.addon.metadata">
    <summary>Truyền hình SCTV</summary>
    <description>Nhóm kênh chính thức của truyền hình SCTV</description>
    <platform>all</platform>
  </extension>
</addon>

<addon id="plugin.video.hieuhien.vn.snagfilms"
       name="[COLOR yellow][B]Snagfilms[/B][/COLOR]"
       version="1.0.10"
       provider-name="t1m">
  <requires>
    <import addon="xbmc.python" version="2.1.0"/>
  </requires>
  <extension point="xbmc.python.pluginsource"
            library="default.py">
        <provides></provides>
  </extension>
  <extension point="xbmc.addon.metadata">
    <summary lang="en">Snagfilms Video Addon</summary>
    <description lang="en">SnagFilms offers a broad collection of great movies you can watch right now</description>
    <disclaimer lang="en">Feel free to use this script. For information visit the wiki.</disclaimer>
    <platform>all</platform>
    <language>en</language>
    <license>GNU GENERAL PUBLIC LICENSE. Version 2, June 1991</license>
    <forum>http://forum.kodi.tv/showthread.php?tid=198859</forum>
    <website>http://www.snagfilms.com</website>
    <email></email>
    <source>https://github.com/learningit/plugin.video.snagfilms</source>
  </extension>
</addon>

<addon
  id="plugin.video.hieuhien.vn.talktv"
  version="0.1.0"
  name="[COLOR violet][B]TalkTV.vn[/B][/COLOR]"
  provider-name="MrOdin">
  <requires>
	<import addon="xbmc.python" version="2.1.0" />
    <import addon="script.common.plugin.cache" version="2.5.2" />
    <import addon="script.module.requests" version="2.4.3"/>
    <import addon="service.vnmusic" version="1.0.2"/>
  </requires>
  <extension point="xbmc.python.pluginsource"
            library="talktv.py">
        <provides></provides>
  </extension>
  <extension point="xbmc.addon.metadata">
    <summary>Truyền hình trực tiếp, stream game, xem trực tiếp game</summary>
    <description>TalkTV là hệ thống cho phép stream và xem trực tiếp hoàn toàn miễn phí được xây dựng cho cộng đồng Việt.</description>
    <platform>all</platform>
  </extension>
</addon>

<addon
	id="plugin.video.hieuhien.vn.tubemotion"
	version="1.0.1"
	name="[COLOR violet][B]TubeMotion[/B][/COLOR]"
	provider-name="bacha">
	<requires>
	</requires>
	<extension point="xbmc.python.pluginsource" library="default.py">
		<provides></provides>
	</extension>
	<extension point="xbmc.addon.metadata">
	<summary>YouTube and Dailymotion Channels</summary>
	<description>Tổng hợp các kênh Youtube và Dailymotion. Addon này được viết lại dựa trên netmedia và chantube addons.</description>
	<platform>all</platform>
</extension>
</addon>

<addon
	id="plugin.video.hieuhien.vn.tvvn"
	version="0.9.9"
	name="[COLOR violet][B]TV Viet Nam[/B][/COLOR]"
	provider-name="Binh Nguyen">
	<requires>
		<import addon="xbmc.python" version="2.1.0"/>
	</requires>
	<extension point="xbmc.python.pluginsource" library="tvvn.py">
		<provides></provides>
	</extension>
	<extension point="xbmc.addon.metadata">
		<platform>all</platform>
		<language>en vi</language>
		<website>http://zecoj.com</website>
		<source>https://github.com/zecoj/xbmc-tvvn</source>
		<summary lang="en">TV Viet Nam</summary>
		<summary lang="vi">TV Việt Nam</summary>
		<description lang="en">This plugin allows you to watch live TV channels or listen to radio stations in Viet Nam or from overseas providers straight from the XBMC interface, thus eliminating the needs for using browsers and flashplayer, etc. Bug report at: zecoj.com. If you enjoy using the plugin, consider donate via PayPal to b [AT] zecoj [DOT] com</description>
		<description lang="vi">Xem trực tiếp các kênh truyền hình và các đài phát thanh từ Việt Nam và hải ngoại. If you enjoy using the plugin, consider donate via PayPal to b [AT] zecoj [DOT] com</description>
		<disclaimer lang="en">All live streams are pulled from online providers and in no way represent my views or opinions. I also hold no control over the quality of the streams nor that of your internet connection :)</disclaimer>
		<disclaimer lang="vi">Tất cả live streams được tải về từ các nhà cung cấp dịch vụ. Tác giả phần mềm này không chịu trách nhiệm về nội dung của chúng.</disclaimer>
		<license>GNU GENERAL PUBLIC LICENSE. Version 3, 29 June 2007</license>
	</extension>
</addon>

	<addon id="plugin.video.hieuhien.vn.viettube.channels" name="[COLOR violet][B]VietTube Channels[/B][/COLOR]" version="4.1" provider-name="V137">
		<requires>
			<import addon="xbmc.python" version="2.1.0"/>
		</requires>
		<extension point="xbmc.python.pluginsource" library="addon.py">
			<provides></provides>
		</extension>
		<extension point="xbmc.addon.metadata">
			<platform>all</platform>
			<summary lang="en">Viet YouTube channels</summary>
			<language/>
			<description lang="en">Viet YouTube channels</description>
		</extension>
	</addon>

<addon
  id="plugin.video.hieuhien.vn.viettv24free"
  version="1.0.9"
  name="[COLOR violet][B]viettv24free[/B][/COLOR]"
  provider-name="Dknight - mod by bacha">
  <requires>
		<import addon="script.module.beautifulsoup" version="3.0.8"/>
		<import addon="script.module.simplejson" />
		<import addon="script.module.t0mm0.common" version="1.1.0"/>
  </requires>
  <extension point="xbmc.python.pluginsource"
            library="default.py">
        <provides></provides>
  </extension>
  <extension point="xbmc.addon.metadata">
    <summary>viettv24free+</summary>
    <description>viettv24 for free</description>
    <platform>all</platform>
  </extension>
</addon>

<addon
  id="plugin.video.hieuhien.vn.vkool"
  version="0.0.6"
  name="[COLOR lime][B]vkool.net[/B][/COLOR]"
  provider-name="traitravinh">
  <requires>
    <import addon="xbmc.python" version="2.1.0" optional="true"/>
    <import addon="script.module.requests" version="2.4.3" />
    <import addon="script.common.plugin.cache" version="2.5.2" />
    <import addon="script.module.simple.downloader" version="1.9.4" />
  </requires>
  <extension point="xbmc.python.pluginsource"
            library="vkool.py">
        <provides></provides>
  </extension>
  <extension point="xbmc.addon.metadata">
    <summary>Watch Movies</summary>
    <description>Watch Movies on vkool.net</description>
    <platform>all</platform>
  </extension>
</addon>


<addon id="plugin.video.webgiaitri" version="1.1.9" name="[COLOR violet][B]Web Giai Tri[/B][/COLOR]" provider-name="chanmodoi">
	<requires>
		<import addon="xbmc.python" version="2.1.0" />
		<import addon="script.module.parsedom" version="0.9.1"/>
		<import addon="plugin.video.youtube" version="5.1.8"/>
		<import addon="script.module.requests" version="2.7.0" />
		<import addon="script.module.beautifulsoup4" version="4.3.1"/>
		<import addon="script.module.html5lib" version="0.999.0"/>

	</requires>
	<extension point="xbmc.python.pluginsource" library="addon.py">
		<provides></provides>
	</extension>
	<extension point="xbmc.addon.metadata">
		<summary>Web Giai Tri</summary>
		<description>See videos and photos from some Vietnamese site: xem.com, ngamvn.com, haivainoi.com, gioitre.net, Beat.vn, talktv.vn </description>
		<platform>all</platform>
		<language>vi</language>
		<license>GNU GENERAL PUBLIC LICENSE. Version 2, June 1991</license>
		<forum></forum>
		<website>https://github.com/chanmodoi</website>
		<source>https://github.com/chanmodoi</source>
		<disclaimer></disclaimer>
		<email></email>
		<broken></broken>
	</extension>
</addon>

	<addon id="plugin.video.hieuhien.vn.xemphim73" version="1.1" name="[COLOR lime][B]XemPhim 73[/B][/COLOR]" provider-name="V137">
		<requires>
			<import addon="xbmc.python" version="2.1.0"/>
			<import addon="script.module.requests" version="2.6.0"/>
			<import addon="script.module.urlresolver" version="1.0.0"/>
			<import addon="script.module.xbmcswift2" version="1.3.1" />
		</requires>
		<extension point="xbmc.python.pluginsource" library="default.py">
			<provides></provides>
		</extension>
		<extension point="xbmc.addon.metadata">
			<summary>XemPhim 73</summary>
			<description>XemPhim 73 (Vietnamese)</description>
			<platform>all</platform>
		</extension>
	</addon>

	<addon id="plugin.video.hieuhien.vn.xemphimmienphi" version="1.1" name="[COLOR lime][B]XemPhimMienPhi[/B][/COLOR]" provider-name="V137">
		<requires>
			<import addon="xbmc.python" version="2.1.0"/>
			<import addon="script.module.requests" version="2.6.0"/>
		</requires>
		<extension point="xbmc.python.pluginsource" library="default.py">
			<provides></provides>
		</extension>
		<extension point="xbmc.addon.metadata">
			<summary>XemPhimMienPhi</summary>
			<description>XemPhimMienPhi (Vietnamese)</description>
			<platform>all</platform>
		</extension>
	</addon>

<addon id="plugin.video.hieuhien.vn.xemphimso"  version="1.9" name="[COLOR green]*[/COLOR]XemPhimSo" provider-name="traitravinh, V137">
	<requires>
		<import addon="xbmc.python" version="2.1.0" />
		<import addon="script.module.requests" version="2.4.3" />
		<import addon="script.module.beautifulsoup" version="3.2.1" />
		<import addon="script.module.beautifulsoup4"/>
	</requires>
	<extension point="xbmc.python.pluginsource" library="xemphimso.py">
		<provides></provides>
	</extension>
	<extension point="xbmc.addon.metadata">
		<summary>XemPhimSo</summary>
		<description>XemPhimSo (Vietnamese)</description>
		<platform>all</platform>
	</extension>
</addon>


<addon id="plugin.video.hieuhien.vn.xemvn" version="1.0.0" name="[COLOR violet][B]Xem.Vn[/B][/COLOR]" provider-name="chanmodoi">
	<requires>
		<import addon="xbmc.python" version="2.1.0" />
		<import addon="script.module.parsedom" version="0.9.1"/>
		<import addon="plugin.video.youtube" version="5.1.8"/>
		<import addon="script.module.requests" version="2.7.0" />
	</requires>
	<extension point="xbmc.python.pluginsource" library="addon.py">
		<provides></provides>
	</extension>
	<extension point="xbmc.addon.metadata">
		<summary>Xem.Vn</summary>
		<description>See videos from sites: xem.vn</description>
		<platform>all</platform>
		<language>vi</language>
		<license>GNU GENERAL PUBLIC LICENSE. Version 2, June 1991</license>
		<forum></forum>
		<website>https://github.com/chanmodoi</website>
		<source>https://github.com/chanmodoi</source>
		<disclaimer></disclaimer>
		<email></email>
		<broken></broken>
	</extension>
</addon>

	<addon id="plugin.video.hieuhien.vn.xomgiaitri" version="1.2.0" name="[COLOR lime][B]XomGiaiTri[/B][/COLOR]" provider-name="V137">
		<requires>
			<import addon="xbmc.python" version="2.1.0"/>
		</requires>
		<extension point="xbmc.python.pluginsource" library="default.py">
			<provides></provides>
		</extension>
		<extension point="xbmc.addon.metadata">
			<summary>XomGiaiTri</summary>
			<description>XomGiaiTri (Vietnamese)</description>
			<platform>all</platform>
		</extension>
	</addon>

<addon id="plugin.video.hieuhien.vn.xsharefree" name="Xshare Media Center" version="3.5.8.4.10" provider-name="thaitni">
    <requires>
        <import addon="xbmc.python" version="2.1.0"/>
		<import addon="script.video.F4mProxy" optional="true"/>
		<import addon="script.module.youtube.dl" optional="true"/>
    </requires>
    <extension point="xbmc.python.pluginsource" library="xshare.py">
        <provides>video</provides>
    </extension>
    <extension point="xbmc.addon.metadata">
        <summary>Xshare - XBMC HD Video</summary>
		<description lang="en">Tìm và Xem HD Video trên XBMC từ: fshare.vn, 4share.vn, vaphim.com, ifile.tv, phimfshare.com, fptplay.net, hdvietnam.com, megabox.vn, dangcaphd.com, hayhaytv.vn, hdviet.com, pubvn.net, vuahd.tv, phimmoi.net, hdonline.vn, phim3s.net, kenh88.com, phimdata.com, phimsot.com, phim47.com</description>
		<platform>all</platform>
		<language>en</language>
		<license>GNU General Public License - v2</license>
		<source>https://github.com/thaitni/xbmc.repo.xshare</source>
		<email>thai@thanhthai.net</email>
    </extension>
</addon>

	<addon id="plugin.video.hieuhien.vn.xuongphim" version="1.2" name="[B]XuongPhim.TV[/B]" provider-name="V137">
		<requires>
			<import addon="xbmc.python" version="2.1.0"/>
			<import addon="script.module.requests" version="2.6.0"/>
			<import addon="script.module.xbmcswift2" version="1.3.1" />
		</requires>
		<extension point="xbmc.python.pluginsource" library="default.py">
			<provides></provides>
		</extension>
		<extension point="xbmc.addon.metadata">
			<summary>XuongPhim.TV</summary>
			<description>XuongPhim.TV (Vietnamese)</description>
			<platform>all</platform>
		</extension>
	</addon>

<addon
  id="plugin.video.hieuhien.vn.yeuphim"
  version="0.6"
  name="[COLOR lime][B]Yêu Phim[/B][/COLOR]"
  provider-name="thongld">
  <requires>
    <import addon="xbmc.python" version="2.1.0"/>
  </requires>
  <extension point="xbmc.python.pluginsource" library="default.py">
        <provides></provides>
  </extension>
  <extension point="xbmc.addon.metadata">
    <summary></summary>
    <description></description>
    <platform>all</platform>
  </extension>
</addon>

<addon id="plugin.video.hieuhien.vn.zingtv" name="[B]Zing TV[/B]" version="1.0.1" provider-name="">
	<requires>
		<import addon="xbmc.python" version="2.6.0"/>
		<import addon="script.module.simplejson" optional="true"/>
		<import addon="script.common.plugin.cache" version="2.5.5"/>
	</requires>
	<extension point="xbmc.python.pluginsource" library="default.py">
		<provides></provides>
	</extension>
	<extension point="xbmc.addon.metadata">
		<summary lang="en"></summary>
		<description lang="en"></description>
		<disclaimer lang="en"></disclaimer>
		<platform>all</platform>
	</extension>
</addon>

<addon
	id="plugin.video.HieuHienLiveShow"
	version="1.0.1"
	name="[COLOR lime][B]HieuHienLiveShow[/B][/COLOR]"
	provider-name="Hieuhien.vn">
	<requires>
		<import addon="script.module.simplejson" />
		<import addon="xbmc.python" version="2.1.0"/>
		<import addon="script.module.simple.downloader" version="1.9.4" />
	</requires>
	<extension point="xbmc.python.pluginsource" library="liveshow.py">
		<provides></provides>
	</extension>
	<extension point="xbmc.addon.metadata">
		<summary>[COLOR red]Hieuhien.vn[/COLOR]</summary>
		<description>[COLOR lime][B]Add-on xem các show diễn ca nhạc, hài kịch online[/B][/COLOR]</description>
		<disclaimer>Tất cả nội dung được lấy từ Internet - chúng tôi hoàn toàn không chịu trách nhiệm về bản quyền hay độ ổn định của chương trình</disclaimer>
		<platform>all</platform>
	</extension>
</addon>

<addon
	id="plugin.video.HieuHienTV"
	version="1.0.1"
	name="[COLOR lime][B]HieuHienTV[/B][/COLOR]"
	provider-name="Hieuhien.vn">
	<requires>
		<import addon="script.module.simplejson" />
		<import addon="xbmc.python" version="2.1.0"/>
		<import addon="script.module.simple.downloader" version="1.9.4" />
	</requires>
	<extension point="xbmc.python.pluginsource" library="tvchannel.py">
		<provides>video</provides>
	</extension>
	<extension point="xbmc.addon.metadata">
		<summary>[COLOR red]Hieuhien.vn[/COLOR]</summary>
		<description>[COLOR lime][B]Add-on Xem truyền hình Online được Hieuhien.vn viết lại dựa trên addon ITV Plus của tác giả itv member[/B][/COLOR]</description>
		<disclaimer>Tất cả nội dung được lấy từ Internet - chúng tôi hoàn toàn không chịu trách nhiệm về bản quyền hay độ ổn định của chương trình</disclaimer>
		<platform>all</platform>
	</extension>
</addon>

<addon id="plugin.video.itvplus"
       version="2.5.0.264"
       name="[COLOR ffff0000]*ITV*[/COLOR]Plus"
       provider-name="itv member">
    <requires>
        <import addon="xbmc.python" version="2.1.0" optional="true" />
		<import addon="script.module.requests" version="1.0" />
    </requires>
    <extension point="xbmc.python.pluginsource" library="default.py">
        <provides></provides>
    </extension>
    <extension point="xbmc.service" library="autorun.py" start="startup">
    </extension>
    <extension point="xbmc.addon.metadata">
        <summary>ITV Entertainment</summary>
        <description>
* Addon được ITVPlus xây dựng dựa vào nguồn dữ liệu trên internet.
* Với mục đích phục vụ nhu cầu giải trí cho cộng đồng Kodi. Chúng tôi đã tốn nhiều thời gian và công sức để tạo ra sản phẩm, vì vậy mong các tổ chức và cá nhân tuân thủ các quy định sau:
- Không tự ý sử dụng mã nguồn của addon khi chưa có sự đồng ý của nhóm lập trình viên ITVPlus.
- Không tự ý chỉnh sửa lại addon và chia sẻ, quảng cáo phục vụ cho nhu cầu lợi ích của một cá nhân hay tập thể nào đó.
	    </description>
	    <disclaimer lang="en">[COLOR ffff0000]Data được chia sẻ trên internet. Chúng tôi không chịu mọi trách nhiệm pháp lý.[/COLOR]</disclaimer>
        <platform>all</platform>
    </extension>
</addon>

<!--suppress ALL -->
<addon id="plugin.video.link__tester" version="0.0.1" name="URLResolver Link Tester" provider-name="Echo Coder">
    <requires>
        <import addon="xbmc.python" version="2.1.0"/>
        <import addon="script.module.urlresolver" version="2.2.0"/>
        <import addon="script.module.echo"/>
    </requires>
    <extension point="xbmc.python.pluginsource" library="default.py">
        <provides>video</provides>
    </extension>
    <extension point="xbmc.addon.metadata">
        <summary>URLResolver Link Tester Addon - Forked from TK Norris</summary>
        <description></description>
        <platform>all</platform>
	</extension>
</addon>

<addon
  id="plugin.video.sctv.hieuhien.vn"
  version="1.0"
  name="SCTV"
  provider-name="thong.ld">
  <requires>
    <import addon="xbmc.python" version="2.1.0"/>
    <import addon="script.module.xbmcswift2" version="1.3.1" />
    <import addon="script.module.requests" version="1.0" />
  </requires>
  <extension library="default.py" point="xbmc.python.pluginsource">
    <provides></provides>
  </extension>
  <extension point="xbmc.addon.metadata">
    <summary>Truyền hình SCTV</summary>
    <description>Nhóm kênh chính thức của truyền hình SCTV</description>
    <platform>all</platform>
  </extension>
</addon>

	<addon id="plugin.video.v137.phimlt"  version="2.2" name="PhimLT.com" provider-name="V137">
		<requires>
			<import addon="xbmc.python" version="2.1.0" />
			<import addon="script.module.requests" version="2.6.0"/>
			<import addon="script.module.urlresolver" version="1.0.0"/>
			<import addon="script.module.xbmcswift2" version="1.3.1" />
		</requires>
		<extension library="default.py" point="xbmc.python.pluginsource">
			<provides>video</provides>
		</extension>
		<extension point="xbmc.addon.metadata">
			<summary>PhimLT.com</summary>
			<description>PhimLT.com (Vietnamese)</description>
			<platform>all</platform>
		</extension>
	</addon>

<addon id="plugin.video.xbmchubmaintenance" version="2.1.6"
	name="Maintenance Tool" provider-name="tvaddons.ag">
  <requires>
    <import addon="xbmc.python" version="2.1.0"/>
    <import addon="plugin.video.youtube" />
    <import addon="script.module.addon.common" />
    <import addon="script.module.metahandler" />
  </requires>
  <extension point="xbmc.python.pluginsource" library="default.py">
        <provides>executable</provides>
  </extension>
  <extension point="xbmc.addon.metadata">
    <summary lang="en">Maintenance Tool</summary>
    <description lang="en">Maintenance Tool is your one stop tool for all fixes and information.</description>
    <platform>all</platform>
    <forum>http://forums.tvaddons.ag/forums/130-MAINTENANCE-TOOL</forum>
    <website>http://www.tvaddons.ag/</website>
  </extension>
</addon>

<addon id="program.plexus"
       name="Plexus"
       version="0.1.4"
       provider-name="enen92, TV ADDONS">
  <requires>
    <import addon="xbmc.python" version="2.1.0"/>
    <import addon="script.module.requests" />
  </requires>
  <extension point="xbmc.python.pluginsource"
            library="default.py">
        <provides>executable</provides>
  </extension>

  <extension point="xbmc.addon.metadata">
    <summary>SopCast and AceStream for Kodi</summary>
    <description lang="en">Plexus - Any complex structure containing an intricate network of parts. Plexus brings native peer-to-peer support (AceStream and SopCast) for Kodi Entertainment Center for several platforms.[CR][CR]Documentation: (missing)</description>
    <description lang="pt">Plexus - Uma estrutura complexa constituída por uma rede de partes. O Plexus adiciona suporte peer-to-peer nativo (AceStream e Sopcast) ao Kodi Entertainment Center para várias plataformas.[CR][CR]Documentação: (em falta)</description>
    <disclaimer lang="en">The author does not host nor distribute any of the content you may watch using this addon. The author has no part in the development of any included technologies. When seeking help in Kodi's forum please respect rules (http://kodi.wiki/view/Forum_rules).</disclaimer>
    <disclaimer lang="pt">Os autores não alojam nem distribuem nenhum do conteúdo que poderá ser reproduzido a partir deste addon. Os autores não têm qualquer parte no desenvolvimento de qualquer uma das tecnologias. Se procurar ajuda no fórum oficial do Kodi por favor respeite as regras do fórum (http://kodi.wiki/view/Forum_rules).</disclaimer>
    <forum>http://forums.tvaddons.ag</forum>
    <platform>all</platform>
  </extension>
</addon>

<addon id="repository.cantobumedia" name="Cantobu Media Repository" version="1.0.0" provider-name="phuoclv">
	<extension point="xbmc.addon.repository" name="Official XBMC.org Add-on Repository">
		<info compressed="true">https://raw.githubusercontent.com/phuoclv/repository.cantobumedia/master/addons.xml</info>
		<checksum>https://raw.githubusercontent.com/phuoclv/repository.cantobumedia/master/addons.xml.md5</checksum>
		<datadir zip="true">https://raw.githubusercontent.com/phuoclv/repository.cantobumedia/master</datadir>
		<hashes>true</hashes>
	</extension>
	<extension point="xbmc.addon.metadata">
		<summary>Cantobu Media Entertainment</summary>
		<description>Giải trí trên XBMC/Kodi</description>
		<disclaimer></disclaimer>
		<platform>all</platform>
	</extension>
</addon>

<addon id="repository.datho.xbmc-plugins" name="Datho Add-on Repository" version="1.0.0" provider-name="Datho-Digital">
    <extension point="xbmc.addon.repository" name="Datho Add-on Repository">
        <info compressed="false">http://raw.github.com/datho/datho-xbmc-repo/master/addons.xml</info>
        <checksum>http://raw.github.com/datho/datho-xbmc-repo/master/addons.xml.md5</checksum>
        <datadir zip="true">http://raw.github.com/datho/datho-xbmc-repo/master/repo/</datadir>
	</extension>
	<extension point="xbmc.addon.metadata">
		<summary>Install Add-ons from Datho Repository</summary>
		<description>Add-ons for XBMC</description>
		<disclaimer>by datho</disclaimer>
		<platform>all</platform>
	</extension>
</addon>

<addon id="repository.dk-xbmc-repaddon" name="dk-xbmc-repaddon Add-on Repository" version="1.0.5" provider-name="dk-xbmc-repaddon">
	<extension point="xbmc.addon.repository" name="dk-xbmc-repaddon Add-on Repository">
		<info compressed="false">http://raw.githubusercontent.com/dknlght/dkodi/master/addons.xml</info>
		<checksum>http://raw.githubusercontent.com/dknlght/dkodi/master/addons.xml.md5</checksum>
		<datadir zip="true">http://raw.githubusercontent.com/dknlght/dkodi/master/</datadir>
	</extension>
	<extension point="xbmc.addon.metadata">
		<summary>Install Add-ons from dk Add-on Repository</summary>
		<description>Video plug-ins for XBMC</description>
		<disclaimer></disclaimer>
		<platform>all</platform>
	</extension>
</addon>

<addon id="repository.exodus" version="1.0.1" name="Exodus repository" provider-name="Exodus">
	<extension point="xbmc.addon.repository" name="Exodus repository">
		<dir>
			<info compressed="false">https://offshoregit.com/tvaresolvers/tva-common-repository/raw/master/addons.xml</info>
			<checksum>https://offshoregit.com/tvaresolvers/tva-common-repository/raw/master/addons.xml.md5</checksum>
			<datadir zip="true">https://offshoregit.com/tvaresolvers/tva-common-repository/raw/master/zips/</datadir>
		</dir>
		<info compressed="false">https://offshoregit.com/exodus/addons.xml</info>
		<checksum>https://offshoregit.com/exodus/addons.xml.md5</checksum>
		<datadir zip="true">https://offshoregit.com/exodus/</datadir>
	</extension>
	<extension point="xbmc.addon.metadata">
		<summary lang="en">Exodus repository</summary>
		<description lang="en">Exodus repository</description>
		<platform>all</platform>
	</extension>
</addon>


<addon
	id="repository.hieuhien.vn"
	version="1.0.0"
	name="[B][COLOR lime]Hieuhien.vn Repository[/COLOR][/B]"
	provider-name="Hieuhien.vn">
	<requires>
		<import addon="xbmc.addon" version="12.0.0"/>
	</requires>
	<extension point="xbmc.addon.repository"
		name="[COLOR lime][B]Hieuhien.vn Repository[/B][/COLOR]">
		<info compressed="true">https://raw.github.com/hieuhienvn/hieuhien.vn/master/addons.xml</info>
		<checksum>https://raw.github.com/hieuhienvn/hieuhien.vn/master/addons.xml.md5</checksum>
		<datadir zip="true">https://github.com/hieuhienvn/hieuhien.vn/raw/master/zips/</datadir>
	</extension>
	<extension point="xbmc.addon.metadata">
		<summary lang="en">Install addon from Hieuhien.vn's repository</summary>
		<description lang="en">[COLOR red][B]Hieuhien.vn[/COLOR]-[COLOR lime]Repository tập hợp các addon và repository giải trí online trên XBMC - Kodi[/B][/COLOR]</description>
		<disclaimer lang="en">Mọi nội dung được lấy từ Internet vì vậy chúng tôi không chịu trách nhiệm về chất lượng cũng như sự ổn định</disclaimer>
		<email>contact@hieuhien.vn</email>
		<platform>all</platform>
	</extension>
</addon>

<addon id="repository.HopDenTV" name="HopDenTV REPO" version="1.0.3" provider-name="HopDenTV">
	<extension point="xbmc.addon.repository" name="HopDenTV Addon Repository">
		<info compressed="false">http://hdtvblackbox.com/HopDenTV_REPO/HopDenTV-Repo.xml</info>
		<checksum>http://hdtvblackbox.com/HopDenTV_REPO/HopDenTV-Repo.md5</checksum>
		<datadir zip="true">http://hdtvblackbox.com/HopDenTV_REPO/Zips/</datadir>
	</extension>
	<extension point="xbmc.addon.metadata">
		<summary>Install HopDenTV REPO</summary>
		<description>Download and install addons from HopDenTV REPO: Watch free Movies and TV shows from many different sources</description>
		<platform>all</platform>
	</extension>
</addon>

<addon id="repository.itvplus"
		name="[COLOR ffff0000]ITVPLUS[/COLOR] Repository"
		version="1.1.0"
		provider-name="ITV member">
  <requires>
    <import addon="xbmc.addon" version="12.0.0"/>
  </requires>
	<extension point="xbmc.addon.repository"
		name="ITV Add-on's Repository">
		<info compressed="true">http://xbmc.itvplus.net/REPO/addons.xml</info>
		<checksum>http://xbmc.itvplus.net/REPO/addons.xml.md5</checksum>
		<datadir zip="true">http://xbmc.itvplus.net/REPO</datadir>
	</extension>
	<extension point="xbmc.addon.metadata">
		<summary lang="en">Entertainment</summary>
		<description lang="en">Download and install addons from ITV Repository</description>
		<language>en</language>
		<platform>all</platform>
		<email>kodi.itvplus@gmail.com</email>
	</extension>
</addon>

    <addon id="repository.kodi-i4a-repo" name="i4atv" version="1.0.6" provider-name="Inside 4ndroid">
        <requires>
            <import addon="xbmc.addon" version="12.0.0"/>
        </requires>
        <extension point="xbmc.addon.repository" name="i4atv">
            <info compressed="false">https://raw.githubusercontent.com/Inside4ndroid/kodi-i4a-repo/master/_repo/addons.xml</info>
            <checksum>https://raw.githubusercontent.com/Inside4ndroid/kodi-i4a-repo/master/_repo/addons.xml.md5</checksum>
            <datadir zip="true">https://raw.githubusercontent.com/Inside4ndroid/kodi-i4a-repo/master/_repo/</datadir>
            <hashes>false</hashes>
        </extension>
        <extension point="xbmc.addon.metadata">
            <summary>Inside 4ndroid Kodi Addons</summary>
            <description>Inside 4ndroid Kodi Addons</description>
            <platform>all</platform>
    </extension>
</addon>

<addon id="repository.kodi4vn" name="Kodi4VN's REPO" version="1.3" provider-name="ThongLD">
	<extension point="xbmc.addon.repository" name="ThongLD's Addon Repository">
		<info compressed="false">http://thong.viettv24.com/kodi4vn/addons.xml</info>
		<checksum>http://thong.viettv24.com/kodi4vn/addons.xml.md5</checksum>
		<datadir zip="true">http://thong.viettv24.com/kodi4vn/</datadir>
	</extension>
	<extension point="xbmc.addon.metadata">
		<summary>Install Kodi4VN Addons</summary>
		<description>Download and install addons from Kodi4VN's Repo: Best addons for Vietnamesse</description>
		<platform>all</platform>
	</extension>
</addon>

<addon id="repository.lambda" name="lambda Add-on repository" version="1.1.0" provider-name="lambda">
	<extension point="xbmc.addon.repository" name="lambda Add-on repository">
		<dir>
			<info compressed="false">http://raw.github.com/lambda81/lambda-repo/master/addons.xml</info>
			<checksum>http://raw.github.com/lambda81/lambda-repo/master/addons.xml.md5</checksum>
			<datadir zip="true">http://raw.github.com/lambda81/lambda-repo/master/</datadir>
		</dir>
		<info compressed="false">https://offshoregit.com/lambda81/lambda-repo/addons.xml</info>
		<checksum>https://offshoregit.com/lambda81/lambda-repo/addons.xml.md5</checksum>
		<datadir zip="true">https://offshoregit.com/lambda81/lambda-repo/</datadir>
	</extension>
	<extension point="xbmc.addon.metadata">
		<summary lang="en">Install Add-ons from lambda</summary>
		<description lang="en">Download and install add-ons from lambda repository.</description>
		<platform>all</platform>
	</extension>
</addon>

<addon id="repository.lnt900" name="Lnt900's Repository" version="1.0.0" provider-name="lnt900">
	<requires>
		<import addon="xbmc.addon" version="12.0.0"/>
	</requires>
	<extension point="xbmc.addon.repository" name="Lnt900 Kodi Add-on Repository">
		<info compressed="true">https://raw.githubusercontent.com/lnt900/kodi.repo.lnt900/master/addons.xml</info>
		<checksum>https://raw.githubusercontent.com/lnt900/kodi.repo.lnt900/master/addons.xml.md5</checksum>
		<datadir zip="true">https://raw.githubusercontent.com/lnt900/kodi.repo.lnt900/master</datadir>
		<hashes>true</hashes>
	</extension>
	<extension point="xbmc.addon.metadata">
		<summary>Created or edited add-ons by Lnt900</summary>
		<description>Video and Service Addons for Vietnamese</description>
		<platform>all</platform>
	</extension>
</addon>

<addon id="repository.metalkettle" name="MetalKettles Addon Repository" version="1.6.2" provider-name="MetalKettle">
	<extension point="xbmc.addon.repository" name="MetalKettles Addon Repository">
		<info compressed="false">http://offshoregit.com/metalkettle/addons.xml</info>
		<checksum>http://offshoregit.com/metalkettle/addons.xml.md5</checksum>
		<datadir zip="true">http://offshoregit.com/metalkettle/zips</datadir>
	</extension>
	<extension point="xbmc.addon.metadata">
		<summary>Install my Addons</summary>
		<description>Download and install addons from MetalKettle</description>
		<platform>all</platform>
	</extension>
</addon>

<addon id="repo.natko1412" name="natko1412 repo" version="2.0.0" provider-name="natko1412">
<extension point="xbmc.addon.repository" name="Natko's Addon Repository">
<info compressed="false">https://offshoregit.com/natko1412/addons.xml</info>
<checksum>https://offshoregit.com/natko1412/addons.xml.md5</checksum>
<datadir zip="true">https://offshoregit.com/natko1412/zips/</datadir>
</extension>
<extension point="xbmc.addon.metadata">
<summary>Install all of Natko's Addons</summary>
<description>Download and install addons by natko1412. For support visit XBMC thread on forum.hr</description>
<platform>all</platform>
</extension>
</addon>

<addon id="repository.otherguysstuff" name="The other Viet Addons" version="1.0.0" provider-name="dk">
	<extension point="xbmc.addon.repository" name="The other Viet Addons">
		<info compressed="false">https://bitbucket.org/dknlght/dk-xbmc-repaddon-rep/raw/master/addons.xml</info>
		<checksum>https://bitbucket.org/dknlght/dk-xbmc-repaddon-rep/raw/master/addons.xml.md5</checksum>
		<datadir zip="true">https://bitbucket.org/dknlght/dk-xbmc-repaddon-rep/raw/master/</datadir>
	</extension>
	<extension point="xbmc.addon.metadata">
		<summary>The other Viet Addons</summary>
		<description>Video plug-ins for XBMC</description>
		<disclaimer></disclaimer>
		<platform>all</platform>
	</extension>
</addon>

<addon id="repository.p2p-streams.xbmc" name="p2p-streams repository" version="1.0.4" provider-name="enen92 - fightnight">
	<extension point="xbmc.addon.repository" name="p2p-streams Repository">
		<info compressed="false">http://p2p-strm.googlecode.com/svn/addons/addons.xml</info>
		<checksum>http://p2p-strm.googlecode.com/svn/addons/addons.xml.md5</checksum>
		<datadir zip="true">http://p2p-strm.googlecode.com/svn/addons</datadir>
	</extension>
	<extension point="xbmc.addon.metadata">
		<summary>p2p-streams repository</summary>
   		<description lang="en">Install P2P-Streams addon for Kodi (SopCast and AceStream). Watch peer-to-peer streams in Kodi without the need for external players!</description>
    		<description lang="pt">Instale o addon P2P-Streams para o Kodi (SopCast e AceStream). Assista a streams peer-to-peer no Kodi sem a necessidade de players externos!</description>
		<disclaimer></disclaimer>
		<platform>all</platform>
	</extension>
</addon>

<addon id="repository.podgod" name="podgod repo" version="1.7" provider-name="podgod">
	<extension point="xbmc.addon.repository" name="PodGod Addon Repository">
		<info compressed="false">http://offshoregit.com/podgod/repo/addons.xml</info>
		<checksum>http://offshoregit.com/podgod/repo/addons.xml.md5</checksum>
		<datadir zip="true">http://offshoregit.com/podgod/repo/zips</datadir>
	</extension>
	<extension point="xbmc.addon.metadata">
		<summary>Install My Addons</summary>
		<description>Download and install addons from podgod!</description>
		<platform>all</platform>
	</extension>
</addon>

<addon id="repository.shani" name="Shanis Addon Repository" version="2.9" provider-name="Shani">
	<extension point="xbmc.addon.repository" name="Shanis Addon Repository">
        <dir>
			<info compressed="false">https://offshoregit.com/tvaresolvers/tva-common-repository/raw/master/addons.xml</info>
			<checksum>https://offshoregit.com/tvaresolvers/tva-common-repository/raw/master/addons.xml.md5</checksum>
			<datadir zip="true">https://offshoregit.com/tvaresolvers/tva-common-repository/raw/master/zips/</datadir>
		</dir>

    <info compressed="false">https://offshoregit.com/Shani-08/main/addons.xml</info>
    <checksum>https://offshoregit.com/Shani-08/main/addons.xml.md5</checksum>
    <datadir zip="true">https://offshoregit.com/Shani-08/main/zips</datadir>

	</extension>
	<extension point="xbmc.addon.metadata">
		<summary>Addons related to XBMC for Zemtv etc</summary>
		<description>Go though the plugins and see what you like</description>
		<platform>all</platform>
	</extension>
</addon>


<addon
	id="repository.thanhnguyenphu"
	version="1.0.0"
	name="[COLOR blue][B]ThanhNguyenPhu Repository[/B][/COLOR]"
	provider-name="thanhnguyenphu">
	<requires>
		<import addon="xbmc.addon" version="12.0.0"/>
	</requires>
	<extension point="xbmc.addon.repository"
		name="[COLOR blue][B]HDPLAY Repository[/B][/COLOR]">
		<info compressed="true">https://raw.github.com/thanhnguyenphu/hdplay.kodi/master/addons.xml</info>
		<checksum>https://raw.github.com/thanhnguyenphu/hdplay.kodi/master/addons.xml.md5</checksum>
		<datadir zip="true">https://github.com/thanhnguyenphu/hdplay.kodi/raw/master/zips/</datadir>
	</extension>
	<extension point="xbmc.addon.metadata">
		<summary lang="en">Install addon from HDPLAY's repository</summary>
		<description lang="en">[COLOR red][B]HDPLAY[/COLOR]-[COLOR blue]Repository tập hợp các addon và repository giải trí online trên XBMC - Kodi[/B][/COLOR]</description>
		<disclaimer lang="en">Mọi nội dung được lấy từ Internet vì vậy chúng tôi không chịu trách nhiệm về chất lượng cũng như sự ổn định</disclaimer>
		<email>https://www.facebook.com/thanh.nguyenphu.3954</email>
		<platform>all</platform>
	</extension>
</addon>

<addon id="repository.traitravinh" name="TraiTraVinh's Testing Repo" version="1.0" provider-name="traitravinh">
	<extension point="xbmc.addon.repository" name="TraiTraVinh's Testing Repo">
		<info compressed="false">https://raw.github.com/traitravinh/traitravinh.repository.xbmc/master/addons.xml</info>
		<checksum>https://raw.github.com/traitravinh/traitravinh.repository.xbmc/master/addons.xml.md5</checksum>
		<datadir zip="true">https://raw.github.com/traitravinh/traitravinh.repository.xbmc/master/zips</datadir>
	</extension>
	<extension point="xbmc.addon.metadata">
		<summary>Testing repo</summary>
		<description>Testing repo</description>
		<disclaimer></disclaimer>
		<platform>all</platform>
	</extension>
</addon>

<addon id="repository.vietccloud" name="VietcCloud Repository" version="1.0.0" provider-name="podgod-clone">
	<extension point="xbmc.addon.repository" name="vietcCloud Addon Repository">
		<info compressed="false">https://github.com/vietccloudtv/repository.vietccloud/raw/master/addons.xml</info>
		<checksum>https://github.com/vietccloudtv/repository.vietccloud/raw/master/addons.xml.md5</checksum>
		<datadir zip="true">https://github.com/vietccloudtv/repository.vietccloud/raw/master/zips</datadir>
	</extension>
	<extension point="xbmc.addon.metadata">
		<summary>Kodi repository</summary>
		<description>Repository for Kodi</description>
		<platform>all</platform>
	</extension>
</addon>

<addon id="repository.vietmedia"
		name="VietMedia Add-ons"
		version="1.0.2"
		provider-name="VietMedia">
  <extension point="xbmc.addon.repository"
		name="VietMedia Add-on Repository">
		<info compressed="true">http://repo.kodi.vn/00-VMFrepo/addons.xml</info>
		<checksum>http://repo.kodi.vn/00-VMFrepo/addons.xml.md5</checksum>
		<datadir zip="true">http://repo.kodi.vn/00-VMFrepo/</datadir>

	</extension>
	<extension point="xbmc.addon.metadata">
		<summary lang="en">VietMedia Entertainment</summary>
		<description lang="en"></description>
		<disclaimer lang="en"></disclaimer>
		<platform>all</platform>
	</extension>
</addon>

<addon id="repository.vnmusic"
		name="Vietnam music Add-ons"
		version="0.9"
		provider-name="MrOdin">
  <requires>
    <import addon="xbmc.addon" version="12.0.0"/>
  </requires>
	<extension point="xbmc.addon.repository"
		name="VietMedia Add-on Repository">
		<info compressed="true">https://raw.githubusercontent.com/tamnm/kodi.mp3.zing.vn/master/addons.xml</info>
		<checksum>https://raw.githubusercontent.com/tamnm/kodi.mp3.zing.vn/master/addons.xml.md5</checksum>
		<datadir zip="true">https://raw.githubusercontent.com/tamnm/kodi.mp3.zing.vn/master</datadir>
		<hashes>true</hashes>
	</extension>
	<extension point="xbmc.addon.metadata">
		<summary lang="en">Vietname music add-ons</summary>
		<description lang="en"></description>
		<disclaimer lang="en"></disclaimer>
		<platform>all</platform>
	</extension>
</addon>

<addon id="repository.xbmc-addons-chinese" name="Chinese Add-ons" version="1.2.0" provider-name="Taxigps">
    <extension point="xbmc.addon.repository" name="Chinese Add-ons">
        <info compressed="true">https://github.com/taxigps/xbmc-addons-chinese/raw/master/addons.xml</info>
        <checksum>https://github.com/taxigps/xbmc-addons-chinese/raw/master/addons.xml.md5</checksum>
        <datadir zip="true">https://github.com/taxigps/xbmc-addons-chinese/raw/master/repo</datadir>
    </extension>
    <extension point="xbmc.addon.metadata">
        <summary>Chinese Add-ons Repository</summary>
        <summary lang="zh">面向中文用户的插件库</summary>
        <description>Download and install add-ons from xbmc-addons-chinese addon repository.[CR][CR]By using this Repository you will be able to take advantage of our cutting edge features developed for chinese people.</description>
        <description lang="zh">从xbmc-addons-chinese库下载安装插件。[CR][CR]通过使用这个程序库，你将能够分享我们为中文用户开发的插件。</description>
        <disclaimer>Taxigps did not make all the add-ons on this repository and is not responsible for their content</disclaimer>
        <disclaimer lang="zh">本库中扩展功能模块不完全由Taxigps开发，对他人提交的内容不承担责任</disclaimer>
        <platform>all</platform>
    </extension>
</addon>

<addon id="repository.xbmchub" name="TVADDONS.ag Addon Repository" version="1.0.6" provider-name="tvaddons.ag">
	<extension point="xbmc.addon.repository" name="TVADDONS.ag Addon Repository">
	<dir>
		<info compressed="false">https://offshoregit.com/tvaresolvers/tva-common-repository/raw/master/addons.xml</info>
		<checksum>https://offshoregit.com/tvaresolvers/tva-common-repository/raw/master/addons.xml.md5</checksum>
		<datadir zip="true">https://offshoregit.com/tvaresolvers/tva-common-repository/raw/master/zips/</datadir>
	</dir>
		<info compressed="false">https://offshoregit.com/xbmchub/xbmc-hub-repo/raw/master/addons.xml</info>
		<checksum>https://offshoregit.com/xbmchub/xbmc-hub-repo/raw/master/addons.xml.md5</checksum>
		<datadir zip="true">https://offshoregit.com/xbmchub/xbmc-hub-repo/raw/master/</datadir>
	</extension>
	<extension point="xbmc.addon.metadata">
		<summary>The Best Third Party Addons for Kodi, Brought to you by TVADDONS.ag</summary>
		<description>The Best Third Party Addons for Kodi, Brought to you by TVADDONS.ag</description>
		<platform>all</platform>
                <forum>http://forums.tvaddons.ag/forums/113-TVADDONS-AG-ADDON-REPOSITORY</forum>
                <website>http://www.tvaddons.ag/</website>
	</extension>
</addon>

<addon id="repository.xunitytalk" name=".[COLOR blue]X[/COLOR]unity[COLOR blue]T[/COLOR]alk Repository" version="1.0.6" provider-name=".[COLOR blue]X[/COLOR]unity[COLOR blue]T[/COLOR]alk">
	<extension point="xbmc.addon.repository" name="Mikey1234 Addon Repository">
		<info compressed="false">http://xty.me/xunitytalk/addons/addons.xml</info>
		<checksum>http://xty.me/xunitytalk/addons/addons.xml.md5</checksum>
		<datadir zip="true">http://xty.me/xunitytalk/addons</datadir>
	</extension>
	<extension point="xbmc.addon.metadata">
		<summary>The Best Third Party Addons for XBMC, .[COLOR blue]X[/COLOR]unity[COLOR blue]T[/COLOR]alk</summary>
		<description>The Best Third Party Addons for XBMC, .[COLOR blue]X[/COLOR]unity[COLOR blue]T[/COLOR]alk</description>
		<platform>all</platform>
	</extension>
</addon>

<addon id="repository.zeus" name="[COLOR black].[/COLOR][COLOR yellow]ZEUS [/COLOR][COLOR white]Repository[/COLOR]" version="1.1.0" provider-name="ZEUS">
	<extension point="xbmc.addon.repository" name="[COLOR black].[/COLOR][COLOR yellow]ZEUS [/COLOR][COLOR white]Repository[/COLOR]">
        <info compressed="false">http://repo.zeusrepo.com/addons.xml</info>
		<checksum>http://repo.zeusrepo.com/addons.xml.md5</checksum>
		<datadir zip="true">http://repo.zeusrepo.com/zips</datadir>
	</extension>
	<extension point="xbmc.addon.metadata">
		<summary>ZEUS KODI XBMC ADDON From Hakamac</summary>
		<description>For Support and news go to http://zeus.video</description>
		<platform>all</platform>
	</extension>
</addon>

<addon id="script.common.plugin.cache" name="Common plugin cache" provider-name="TheCollective" version="2.5.8">
  <requires>
    <import addon="xbmc.python" version="2.24.0" />
  </requires>
  <extension library="default.py" point="xbmc.service" start="startup">
  </extension>
  <extension point="xbmc.addon.metadata">
    <platform>all</platform>
    <summary lang="en">Common caching api for xbmc plugins.</summary>
  </extension>
  <extension library="lib" point="xbmc.python.module" />
</addon>

<addon id="script.grab.fanart"
    name="Grab Fanart" version="0.14.1" provider-name="robweber">
  <requires>
    <import addon="xbmc.python" version="2.19.0"/>
  </requires>
  <extension point="xbmc.python.library" library="default.py" />
  <extension point="xbmc.service" library="service.py" start="login" />
  <extension point="xbmc.addon.metadata">
    <summary lang="en">Exposes fanart as skin properties for slideshows, etc</summary>
    <description lang="en">Uses the Kodi database to grab all fanart from media items and put it into a skin property for use by skins/slideshows as previous version of XBMC allowed.</description>
    <forum>http://forum.kodi.tv/showthread.php?tid=166572</forum>
    <source>https://github.com/robweber/script.grab.fanart</source>
	<website>https://github.com/robweber/script.grab.fanart</website>
    <license>The MIT License</license>
    <platform>all</platform>
    <language></language>
  </extension>
</addon>

<addon id="script.hieuhien.vn.kcleaner" name="Don rac" version="2.6" provider-name="Dalibor Lanik"> <!-- Unique ID and name of the addon -->
  <requires>
    <import addon="xbmc.python" version="2.1.0"/> <!-- Be able to use python in the addon -->
  </requires>
  <extension point="xbmc.python.pluginsource" library="default.py">
        <provides>executable</provides>
  </extension>
  <extension point="xbmc.service" library="service.py" start="startup"> <!-- Extend KODI with a service. Start the addon when starting KODI, and run "default.py" -->
        <provides>executable</provides>
  </extension>
  <extension point="xbmc.addon.metadata"> <!-- Additional addon information -->
    <platform>all</platform>
    <website>http://projects.lanik.org/KodiProject_KCleaner.htm</website>
    <summary lang="en">Clean up temporary files in Kodi.</summary>
    <license>GNU GENERAL PUBLIC LICENSE. Version 2, June 1991</license>
    <forum>http://forum.kodi.tv/showthread.php?tid=307919</forum>
    <email>dalibor@lanik.org</email>
    <description lang="en">Clean up temporary files in Kodi.</description>
    <news>v2.6 [CR]
- Bug fix [CR]
</news>
    <assets>
        <icon>icon.png</icon>
        <fanart>fanart.jpg</fanart>
        <screenshot>resources/screenshot-01.jpg</screenshot>
        <screenshot>resources/screenshot-02.jpg</screenshot>
        <screenshot>resources/screenshot-03.jpg</screenshot>
        <banner>resources/banner.jpg</banner>
        <logo>resources/logo.png</logo>
    </assets>
  </extension>
</addon>

<addon id="script.module.addon.common"
	     name="Common addon methods"
	     version="2.0.0"
	     provider-name="Eldorado (original: t0mm0)">
  <requires>
    <import addon="xbmc.python" version="2.1.0" />
  </requires>
  <extension point="xbmc.python.module" library="lib" />
  <extension point="xbmc.addon.metadata">
    <platform>all</platform>
    <summary lang="en">Collection of commonly used addon routines</summary>
    <description lang="en">Collection of commonly used addon routines to simplify addon development.</description>
    <disclaimer lang="en"></disclaimer>
    <language></language>
    <platform>all</platform>
    <license>GNU GENERAL PUBLIC LICENSE. Version 2, June 1991</license>
    <forum></forum>
    <website></website>
    <email></email>
    <source></source>
  </extension>
</addon>

<addon id="script.module.beautifulsoup"
       name="BeautifulSoup"
       version="3.2.1"
       provider-name="Leonard Richardson (leonardr@segfault.org)">
  <requires>
    <import addon="xbmc.python"
    		version="2.1.0"/>
  </requires>
  <extension point="xbmc.python.module"
             library="lib" />
  <extension point="xbmc.addon.metadata">
    <summary>HTML/XML parser for quick-turnaround applications like screen-scraping</summary>
    <description>Beautiful Soup parses arbitrarily invalid SGML and provides a variety of methods and Pythonic idioms for iterating and searching the parse tree.</description>
    <license>BSD</license>
    <platform>all</platform>
  </extension>
</addon>

<addon id="script.module.beautifulsoup4"
       name="BeautifulSoup4"
       version="4.3.2"
       provider-name="Leonard Richardson (leonardr@segfault.org)">
  <requires>
    <import addon="xbmc.python"
    		version="2.1.0"/>
  </requires>
  <extension point="xbmc.python.module"
             library="lib" />
  <extension point="xbmc.addon.metadata">
    <summary>HTML/XML parser for quick-turnaround applications like screen-scraping</summary>
    <description>Beautiful Soup parses arbitrarily invalid SGML and provides a variety of methods and Pythonic idioms for iterating and searching the parse tree.</description>
    <license>BSD</license>
    <platform>all</platform>
    <website>http://www.crummy.com/software/BeautifulSoup/</website>
  </extension>
</addon>

<addon id="script.module.framework" name="XBMC Plugin Framework" version="1.4" provider-name="">
  <requires>
    <import addon="xbmc.python" version="2.7.0"/>
  </requires>
  <extension point="xbmc.python.module" library="lib" />
  <extension point="xbmc.addon.metadata">
    <summary>Framework for writing xbmc plugins</summary>
    <description></description>
    <license></license>
    <platform>all</platform>
    <website></website>
  </extension>
</addon>

<addon id="script.module.futures"
       name="futures"
       version="2.2.0"
       provider-name="Brian Quinlan">
  <requires>
    <import addon="xbmc.python" version="2.1.0"/>
  </requires>
  <extension point="xbmc.python.module"
             library="lib"/>
  <extension point="xbmc.addon.metadata">
    <summary>A futures implementation for Python</summary>
    <description>Backport of the concurrent.futures package from Python 3.2</description>
    <platform>all</platform>
    <license>BSD</license>
    <source>https://code.google.com/p/pythonfutures/source/browse</source>
    <website>https://code.google.com/p/pythonfutures</website>
  </extension>
</addon>

<addon id="script.module.html5lib"
       name="html5lib-python"
       version="0.999.0"
       provider-name="html5lib">
  <requires>
    <import addon="xbmc.python"
    		version="2.1.0"/>
    <import addon="script.module.six"
                      version="1.4.1"
                     optional="false"/>
  </requires>
  <extension point="xbmc.python.module"
             library="lib" />
  <extension point="xbmc.addon.metadata">
    <summary>Standards-compliant library for parsing and serializing HTML documents and fragments in Python.</summary>
    <description>html5lib is a pure-python library for parsing HTML. It is designed to conform to the WHATWG HTML specification, as is implemented by all major web browsers.</description>
    <platform>all</platform>
    <license>MIT</license>
    <source>https://github.com/html5lib/html5lib-python.git</source>
    <website>https://github.com/html5lib/html5lib-python</website>
  </extension>
</addon>

<addon id="script.module.httplib2" name="httplib2" provider-name=" Joe Gregorio" version="0.8.0">
  <requires>
    <import addon="xbmc.python" version="2.1.0" />
  </requires>
  <extension library="lib" point="xbmc.python.module" />
  <extension point="xbmc.addon.metadata">
        <description lan="en">httplib2 module</description>
        <summary lang="en">httplib2 module</summary>
        <disclaimer lang="en">Visit https://pypi.python.org/pypi/httplib2</disclaimer>
        <license>MIT</license>
        <platform>all</platform>
        <email></email>
        <website>https://pypi.python.org/pypi/httplib2</website>
        <forum></forum>
        <source>https://pypi.python.org/pypi/httplib2</source>
        <language></language>
   </extension>
</addon>

<addon id="script.module.kodiswift" name="kodiswift" provider-name="Aaron Frase (Sinap)" version="0.0.7.1">
  <requires>
    <import addon="xbmc.python" version="2.24.0"/>
  </requires>
  <extension library="lib" point="xbmc.python.module"/>
  <extension point="xbmc.addon.metadata">
    <summary lang="en">A fork of the xbmcswift2 project</summary>
    <description lang="en">A micro framework to enable rapid development of Kodi plugins.</description>
    <platform>all</platform>
    <license>GNU General Public License v3 (GPL-3)</license>
    <source>https://github.com/Sinap/kodiswift</source>
    <email>afrase91@gmail.com</email>
    <language/>
    <website/>
    <forum/>
  </extension>
</addon>

<addon id="script.module.liveresolver"
     name="LiveResolver"
     version="0.1.48"
     provider-name="natko1412">
  <requires>
    <import addon="xbmc.python" version="2.1.0" />
    <import addon="script.module.beautifulsoup" version="3.2.1"/>
    <import addon="script.module.requests"/>
    <import addon="script.module.addon.common" version="2.0.0" />

  </requires>
  <extension point="xbmc.python.module" library="lib" />
  <extension point="xbmc.addon.metadata">
    <platform>all</platform>
    <summary lang="en">Resolve common live video host URL's to be playable in XBMC/Kodi + find links embeded in sites.</summary>
    <description lang="en"></description>
  </extension>
</addon>

<addon id="script.module.livestreamer"
       name="livestreamer"
       version="1.12.0"
       provider-name="Christopher Rosell">
  <requires>
    <import addon="xbmc.python" version="2.1.0"/>
    <import addon="script.module.requests"
                      version="1.1.0"
                     optional="false"/>
    <import addon="script.module.singledispatch"
                      version="3.4.0.3"
                     optional="false"/>
    <import addon="script.module.futures"
                      version="2.2.0"
                     optional="false"/>
  </requires>
  <extension point="xbmc.python.module"
             library="lib"/>
  <extension point="xbmc.addon.metadata">
    <summary>Livestreamer extracts streams from various services</summary>
    <description>Livestreamer is a command-line utility that pipes video streams from various services into a video player, such as VLC. The main purpose of Livestreamer is to allow the user to avoid buggy and CPU heavy flash plugins but still be able to enjoy various streamed content. There is also an API available for developers who want access to the video stream data.</description>
    <platform>all</platform>
    <license>Simplified BSD</license>
    <source>https://github.com/chrippa/livestreamer.git</source>
    <website>http://livestreamer.io</website>
  </extension>
</addon>

<addon id="script.module.mechanize"
	name="Mechanize"
	version="0.2.6"
	provider-name="Tristan Fischer (sphere)">
	<requires>
	<import addon="xbmc.python"
			version="2.1.0"/>
	</requires>
	<extension point="xbmc.python.module"
			 library="lib" />
	<extension point="xbmc.addon.metadata">
		<summary lang="en">Stateful programmatic web browsing in Python, after Andy Lester’s Perl module WWW::Mechanize.</summary>
		<description lang="en">packed for xbmc from https://github.com/jjlee/mechanize</description>
		<disclaimer lang="en">packed for xbmc from https://github.com/jjlee/mechanize</disclaimer>
		<forum></forum>
		<website>http://wwwsearch.sourceforge.net/mechanize/</website>
		<license>BSD</license>
		<platform>all</platform>
		<source>https://github.com/jjlee/mechanize</source>
	</extension>
</addon>

<addon id="script.module.metahandler"
     name="metahandler"
     version="2.9.0"
     provider-name="Eldorado">
  <requires>
    <import addon="xbmc.python" version="2.1.0" />
    <import addon="script.module.simplejson" version="3.3.0"/>
    <import addon="script.module.addon.common" version="2.0.0"/>
    <import addon="script.module.myconnpy" version="1.1.6"/>
  </requires>
  <extension point="xbmc.python.module" library="lib" />
  <extension point="xbmc.addon.metadata">
    <summary lang="en">Downloads Artwork for TV shows, Movies and Music videos for addons and stores them in a local SQLITE database</summary>
    <description lang="en">Queries, stores, and returns metadata for TV shows, Movies and Musicvideos. [CR]Sources:[CR]www.thetvdb.com[CR]www.themoviedb.org[CR]www.imdb.com</description>
    <disclaimer lang="en"></disclaimer>
    <language></language>
    <platform>all</platform>
    <license>GNU GENERAL PUBLIC LICENSE. Version 2, June 1991</license>
    <forum></forum>
    <website></website>
    <email></email>
    <source></source>
  </extension>
</addon>

<addon id="script.module.myconnpy"
       name="MySQL Connector/Python"
       version="1.1.7"
       provider-name="MySQL">
    <requires>
        <import addon="xbmc.python" version="2.1.0"/>
    </requires>
    <extension point="xbmc.python.module" library="lib"/>
    <extension point="xbmc.addon.metadata">
        <summary lang="en">MySQL Connector/Python</summary>
        <description lang="en">MySQL Connector/Python is implementing the MySQL Client/Server protocol completely in Python. This means you don't have to compile anything or MySQL (client library) doesn't even have to be installed on the machine.</description>
        <license>GPLv2</license>
        <platform>all</platform>
        <website>http://dev.mysql.com/doc/connector-python/en/index.html</website>
        <source>http://dev.mysql.com/downloads/connector/python/</source>
    </extension>
</addon>

<addon id="script.module.parsedom" name="Parsedom for xbmc plugins" provider-name="TheCollective" version="2.5.2">
  <requires>
    <import addon="xbmc.python" version="2.1.0" />
  </requires>
  <extension point="xbmc.addon.metadata">
    <platform>all</platform>
    <summary lang="en">Parsedom for xbmc plugins.</summary>
  </extension>
  <extension library="lib" point="xbmc.python.module" />
  <extension point="xbmc.addon.metadata">
        <license>GPLv3</license>
        <platform>all</platform>
        <email></email>
        <website></website>
        <forum>http://forum.xbmc.org/showthread.php?tid=116498</forum>
        <source>https://github.com/HenrikDK/xbmc-common-plugin-functions</source>
        <language></language>
   </extension>
</addon>

<addon id="script.module.pytz" name="pytz" version="2014.2" provider-name="Stuart Bishop, Paul Backhouse">
	<requires>
		<import addon="xbmc.python" version="2.1.0"/>
	</requires>
	<extension point="xbmc.python.module" library="lib"/>
	<extension point="xbmc.addon.metadata">
	    <summary lang="en">World Timezone Definitions for Python.</summary>
	    <description lang="en">pytz brings the Olson tz database into Python. This library allows accurate and cross platform timezone calculations using Python 2.4 or higher. It also solves the issue of ambiguous times at the end of daylight saving time, which you can read more about in the Python Library Reference (datetime.tzinfo).</description>
	    <platform>all</platform>
	    <language></language>
	    <license>MIT</license>
	    <forum></forum>
	    <website>https://pypi.python.org/pypi/pytz/</website>
	    <source>https://github.com/powlo/script.module.pytz</source>
	    <email></email>
	    <disclaimer lang="en">Use at your own risk. The authors accept no liability. May cause permanent and/or catastrophic damage. Side effects include, but are not limited to loss of memory, seizures, sudden fits of rage, sudden fits of melancholy, inability to recall prominent capital cities, lack of respect for authority, fear of cats, temporary and/or permanent black outs. Avoid inhalation. Use in a well ventilated space. Keep away from small children.</disclaimer>
	</extension>
</addon>

<addon id="script.module.requests"
       name="requests"
       version="2.9.1"
       provider-name="kennethreitz, beenje">
  <requires>
    <import addon="xbmc.python" version="2.14.0"/>
  </requires>
  <extension point="xbmc.python.module"
             library="lib" />
  <extension point="xbmc.addon.metadata">
    <summary>Python HTTP for Humans</summary>
    <description>Packed for KODI from https://github.com/kennethreitz/requests</description>
    <platform>all</platform>
    <language></language>
    <license>Apache2</license>
    <forum></forum>
    <website>http://python-requests.org</website>
    <source>https://github.com/beenje/script.module.requests</source>
    <email>beenje AT gmail.com</email>
  </extension>
</addon>

<addon id="script.module.simple.downloader" name="Simple Downloader for xbmc plugins" provider-name="TheCollective" version="1.9.5">
  <requires>
    <import addon="xbmc.python" version="2.1.0" />
    <import addon="script.common.plugin.cache" version="2.5.0" />
    <import addon="script.module.parsedom" version="2.5.1" />
  </requires>
  <extension library="default.py" point="xbmc.service" />
  <extension point="xbmc.addon.metadata">
    <platform>all</platform>
    <summary lang="en">Simple downloader for xbmc plugins.</summary>
  </extension>
  <extension library="lib" point="xbmc.python.module" />
</addon>

<addon id="script.module.simplecache" name="Simple Cache Module" version="1.0.1" provider-name="marcelveldt">
    <requires>
        <import addon="xbmc.python" version="2.24.0"/>
    </requires>
    <extension point="xbmc.python.module" library="lib" />
    <extension point="xbmc.addon.metadata">
        <summary>Provides a simple file- and memory based cache for Kodi addons</summary>
        <description>Provides a simple file- and memory based cache for Kodi addons</description>
        <license>Apache 2.0</license>
        <source>https://github.com/marcelveldt/script.module.simplecache</source>
        <platform>all</platform>
    </extension>
</addon>

<addon id="script.module.simplejson"
       name="simplejson"
       version="3.3.0"
       provider-name="Martijn">
  <requires>
    <import addon="xbmc.python" version="2.1.0"/>
  </requires>
  <extension point="xbmc.python.module"
             library="lib" />
  <extension point="xbmc.addon.metadata">
    <platform>all</platform>
    <language></language>
    <summary lang="en">Simple, fast, extensible JSON encoder/decoder for Python</summary>
    <description lang="en">Simple, fast, extensible JSON encoder/decoder for Python</description>
    <disclaimer lang="en">Code taken from https://pypi.python.org/pypi/simplejson/</disclaimer>
    <license>MIT License, Academic Free License v. 2.1</license>
    <website>https://pypi.python.org/pypi/simplejson/</website>
    <source>https://pypi.python.org/pypi/simplejson/</source>
  </extension>
</addon>

<addon id="script.module.singledispatch"
       name="singledispatch"
       version="3.4.0.3"
       provider-name="Łukasz Langa">
  <requires>
    <import addon="xbmc.python" version="2.1.0"/>
  </requires>
  <extension point="xbmc.python.module"
             library="lib"/>
  <extension point="xbmc.addon.metadata">
    <summary>Single-dispatch generic functions</summary>
    <description>This library brings functools.singledispatch from Python 3.4 to Python 2.6-3.3.</description>
    <platform>all</platform>
    <license>MIT</license>
    <source>https://pypi.python.org/pypi/singledispatch#downloads</source>
    <website>http://docs.python.org/3/library/functools.html#functools.singledispatch</website>
  </extension>
</addon>

<addon id="script.module.six"
       name="six"
       version="1.9.0"
       provider-name="gutworth">
  <requires>
    <import addon="xbmc.python"
    		version="2.1.0"/>
  </requires>
  <extension point="xbmc.python.module"
             library="lib" />
  <extension point="xbmc.addon.metadata">
    <summary>Python 2 and 3 compatibility utilities.</summary>
    <description>Six is a Python 2 and 3 compatibility library. It provides utility functions for smoothing over the differences between the Python versions with the goal of writing Python code that is compatible on both Python versions. See the documentation for more information on what is provided.</description>
    <platform>all</platform>
    <license>MIT</license>
    <source>https://pypi.python.org/pypi/six</source>
    <website>https://pypi.python.org/pypi/six</website>
  </extension>
</addon>

<addon id="script.module.t0mm0.common"
	     name="t0mm0's common stuff"
	     version="2.1.1"
	     provider-name="t0mm0">
  <requires>
    <import addon="xbmc.python" version="2.1.0" />
  </requires>
  <extension point="xbmc.python.module" library="lib" />
  <extension point="xbmc.addon.metadata">
    <platform>all</platform>
    <summary lang="en">Collection of commonly used addon routines</summary>
    <description lang="en">Collection of commonly used addon routines to simplify addon development.</description>
  </extension>
</addon>

<addon id="script.module.unidecode" name="unidecode" version="0.4.16" provider-name="Tomaz Solc (Tomaz.solc@tablix.org)">
	<requires>
		<import addon="xbmc.python" version="2.1.0"/>
	</requires>
	<extension point="xbmc.python.module" library="lib" />
	<extension point="xbmc.addon.metadata">
		<platform>all</platform>
		<language></language>
		<summary lang="en">ASCII transliterations of Unicode text by Sean M. Burke and Tomaz Solc</summary>
		<description lang="en">ASCII transliterations of Unicode text by Sean M. Burke and Tomaz Solc</description>
		<disclaimer lang="en">Code taken from https://pypi.python.org/pypi/Unidecode</disclaimer>
		<license>GNU General Public License v.2</license>
		<website>https://pypi.python.org/pypi/Unidecode</website>
		<source>https://pypi.python.org/pypi/Unidecode</source>
	</extension>
</addon>

<addon id="script.module.urlresolver" name="URLResolver" version="4.0.09" provider-name="Eldorado, tknorris, jsergio">
	<requires>
		<import addon="xbmc.python" version="2.1.0" />
		<import addon="plugin.video.youtube" optional="true" />
		<import addon="script.module.python.twitch" optional="true" />
		<import addon="script.module.cryptopy" version="1.2.6" optional="true" />
	</requires>
	<extension point="xbmc.python.module" library="lib" />
	<extension point="xbmc.python.pluginsource" library="lib/default.py" />
	<extension point="xbmc.addon.metadata">
		<platform>all</platform>
		<summary lang="en">Resolve common video host URL's to be playable in XBMC/Kodi.</summary>
		<summary lang="hr">Prilagodi najčešće URL-ove video izvora kako bi radili u XBMC/Kodiju.</summary>
		<description lang="en">Resolve common video host URL's to be playable in XBMC/Kodi, simplify addon development of video plugins requiring multi video hosts.</description>
		<description lang="hr">Prilagodi najčešće URL-ove video izvora kako bi radili u XBMC/Kodiju, pojednostavnjuje razvoj priključaka za video dodatke koji zahtjevaju višestruke video izvore.</description>
        <source>https://github.com/jsergio123/script.module.urlresolver</source>
	</extension>
</addon>

<addon id="script.mrknow.urlresolver" name="Mrknow URLResolver" version="2016.12.10.1" provider-name="mrknow" >
	<requires>
		<import addon="xbmc.python" version="2.1.0" />
	</requires>
	<extension point="xbmc.python.module" library="lib" />
	<extension point="xbmc.python.pluginsource" library="lib/default.py" />
	<extension point="xbmc.addon.metadata">
		<platform>all</platform>
		<summary lang="en">This addon is almost exact copy Urlresolver from Tknorris repository https://github.com/tknorris/script.module.urlresolver. Resolve common video host URL's to be playable in XBMC/Kodi. Website http://filmkodi.com . Our suport forum https://github.com/mrknow/filmkodi/issues. </summary>
		<description lang="en">This addon is almost exact copy Urlresolver from Tknorris repository https://github.com/tknorris/script.module.urlresolver Resolve common video host URL's to be playable in XBMC/Kodi, simplify addon development of video plugins requiring multi video hosts.</description>
	</extension>
</addon>

<addon id="script.rawmaintenance"
       name="Raw Maintenance"
       version="0.1.12"
       provider-name="Foreverska|Gombeek|Raw Media">
  <requires>
    <import addon="xbmc.python" version="2.1.0"/>
  </requires>
  <extension point="xbmc.python.pluginsource" library="default.py">
        <provides>executable</provides>
  </extension>
  <extension point="xbmc.addon.metadata">
    <platform>all</platform>
    <summary>Raw Maintinance</summary>
    <description>
	Your one stop tool for maintaining your device.
	For support please visit www.no-issue.ca
	Thank you to raw-media.ca for sponsoring the development of this add-on.
    </description>
    <language></language>
    <license></license>
    <source></source>
    <forum></forum>
    <website>www.no-issue.ca</website>
  </extension>
</addon>

<addon id="script.video.F4mProxy"
	     name="F4mProxy"
	     version="2.6.6"
	     provider-name="Shani">
  <requires>
    <import addon="xbmc.python" version="2.1.0" />
    <import addon="script.module.requests" />
  </requires>
  <extension point="xbmc.python.module" library="lib" />
    <extension point="xbmc.python.pluginsource" library="addon.py">
		<provides>executable</provides>
  </extension>

     <extension point="xbmc.addon.repository" name="shani repository">
        <info compressed="false">https://offshoregit.com/Shani-08/main/addons.xml</info>
        <checksum>https://offshoregit.com/Shani-08/main/addons.xml.md5</checksum>
        <datadir zip="true">https://offshoregit.com/Shani-08/main/zips/</datadir>
    </extension>


  <extension point="xbmc.addon.metadata">
    <platform>all</platform>
    <summary lang="en">Proxy for f4m</summary>
    <description lang="en">Use this addon to play F4m v1 and v2 streams</description>
  </extension>
</addon>

<addon id="service.library.data.provider" name="Library Data Provider" provider-name="BigNoid, Martijn" version="0.1.5">
	<requires>
		<import addon="xbmc.addon" version="12.0.0"/>
		<import addon="xbmc.json" version="6.0.0"/>
		<import addon="xbmc.python" version="2.1.0"/>
		<import addon="script.module.simplejson" version="2.0.10"/>
	</requires>
	<extension point="xbmc.python.pluginsource" library="default.py" />
	<extension library="service.py" point="xbmc.service" start="login" />
	<extension point="xbmc.addon.metadata">
		<summary lang="en">Plugin for skins to provide library data throughout the skin.</summary>
		<description lang="en">Plugin for skins to provide library data throughout the skin.</description>
		<disclaimer lang="en">This plugin is not a standalone plugin, your skin must support it.</disclaimer>
		<platform>all</platform>
		<language />
		<license>GNU GENERAL PUBLIC LICENSE Version 2, June 1991</license>
		<forum>http://forum.kodi.tv/showthread.php?tid=210063</forum>
		<website>https://github.com/BigNoid/service.library.data.provider</website>
		<email>big.noid@kodi.tv</email>
		<source>https://github.com/BigNoid/service.library.data.provider</source>
	</extension>
</addon>

<addon id="service.subtitles.opensubtitles"
       name="OpenSubtitles.org"
       version="5.0.16"
       provider-name="amet, opensubtitles">
  <requires>
    <import addon="xbmc.python" version="2.1.0"/>
  </requires>
  <extension point="xbmc.subtitle.module"
             library="service.py" />
  <extension point="xbmc.addon.metadata">
    <summary>OpenSubtitles</summary>
    <description lang="en">Search and download subtitles for movies and TV-Series from OpenSubtitles.org. Search in 75 languages, 4.000.000+ subtitles, daily updates.</description>
	<description lang="at">Pelis and Subtítulos TV en munches llingües, milenta de subtítulos traducíos y xubíos caldía. Descarga llibre dende la fonte, sofitu API, millones d'usuarios.</description>
	<description lang="br">Istitloù Filmoù ha TV e meur a yezh, miliadoù a istitloù troet hag uskarget bemdez. Pellgargadenn digoust diouzh ar vammenn, skoazell an API, millionoù a implijerien.</description>
	<description lang="ca">Subtítols de films i televisió en múltiples idiomes, milers de subtítols traduïts carregats diàriament. Descàrrega gratuïta des de la font, suport de l'API, amb milions d'usuaris.</description>
	<description lang="cs">Titulky k filmům a seriálům v mnoha jazycích, denně tisíce nahraných přeložených titulků. Stažení zadarmo přímo od zdroje, podpora API, milióny uživatelů.</description>
	<description lang="de">Film- und TV-Untertitel in vielen Sprachen, täglicher Upload von tausenden übersetzten Untertiteln. Freier Download von der Quelle, API-Unterstützung, Millionen Nutzer</description>
	<description lang="el">Ταινίες και Σειρές σε όλες τις γλώσσες, χιλιάδες μεταφρασμένοι υπότιτλοι ανεβαίνουν καθημερινά, κατεβάστε δωρεάν , υποστήριξη API από εκατομμύρια χρήστες</description>
	<description lang="eo">Filmaj kaj Televidaj subtekstoj en multaj lingvoj, miloj da tradukitaj subtekstoj ĉiutage alŝutataj. Senpaga elŝuto de fonto, API-subteno, miloj da uzantoj.</description>
	<description lang="es">Películas y Subtítulos en diversos idiomas, miles de subtítulos traducidos subidos diariamente. Descarge gratis, soporte API, millones de usuarios.</description>
	<description lang="et">Sadu Filmi ja TV Serjaalide subtiitrid erinevates keeltes laetakse üles igapäev. tasuta allalaadimine ja abi, rohkem kui miljon kasutajat.</description>
	<description lang="eu">Film eta Telebista azpitituluak hizkuntza anitzetan, milaka azpititulu itzuliak igotzen dira egunero. Doan jaitsi iturburutik, API sostengua, milioika erabiltzaile.</description>
	<description lang="fi">Tekstityksiä useilla kielillä elokuviin ja TV-Sarjoihin, tuhansia uusia tekstityksiä päivittäin, ilmainen lataus, API tuki, miljoonia käyttäjiä.</description>
	<description lang="fr">Les sous-titres de film et téléfilm en plusieurs langues, des milliers de sous-titres traduits tous les jours. Bénéficiez de téléchargements gratuits depuis la source, du support API, une d'une communauté de millions d'utilisateurs.</description>
	<description lang="hi">मूवी और टीवी उपशीर्षक कई भाषाओं में अनुवाद उपशीर्षक के हजारों दैनिक अपलोड की गई। मुफ्त डाउनलोड स्रोत से , एपीआई समर्थन, उपयोगकर्ताओं के लाखों लोगों की ।</description>
	<description lang="hr">Titlovi za filmove i TV na mnogim jezicima, tisuće prijevoda postavljenih svaki dan. Besplatno preuzimanje s izvora, podrška za API, milijuni korisnika.</description>
	<description lang="hu">Film és TV feliratok több nyelven, naponta több ezer lefordított felirat feltöltés. Ingyenes letöltés a forrástól, API támogatás, több millió felhasználó.</description>
	<description lang="id">Subjudul film dan serial TV dalam multibahasa, ribuan subjudul diterjemah dan diunggah setiap harinya. Pengunduhan gratis dari sumber, didukung fitur antarmuka pemrograman aplikasi, dan jutaan pengguna.</description>
	<description lang="is">Textar fyrir myndir og sjónvarpsþ. á mörgum tungumálum, þúsundir af þýddum textum upphlaðið daglega. Frítt niðurhal frá síðu, API stuðningur, milljónir notenda.</description>
	<description lang="it">Sottotitoli di Film e TV in più lingue,migliaia di sottotitoli tradotti caricati ogni giorno.Download gratuito,supporto API, milioni di utenti.</description>
	<description lang="ja">映画やテレビの字幕をさまざまな言語で。毎日数多くの翻訳字幕がアップロードされています。ソースを無料ダウンロード、API 対応、数百万を超えるユーザー。</description>
	<description lang="ka">სუბტიტრები ფილმებისა და ტვ-სთვის მრავალ ენაზე. ათასობიტ თარგმნილი სუბტიტრის ატვირთვა ყოველდღიურად. უდასო ჩამოტვირტვა წყაროდან, API მხარდაჭერა, მილიონობით მომხმარებელი</description>
	<description lang="km">អត្ថបទរឿងសម្រាប់ ខ្សែភាពយន្ត និងកម្មវិធីទូរទស្សន៍​ ជាភាសាជាច្រើន រួមនឹងអត្ថបទរឿងបកប្រែរាប់ពាន់​រឿង​ដែល​ត្រូវបាន​អ័ពឡូដជារៀងរាល់ថ្ងៃ។ ទាញយកដោយឥតគិតថ្លៃពីប្រភពដើម គាំទ្រ API និងមានអ្នកប្រើប្រាស់រាប់លាននាក់។ </description>
	<description lang="ko">Movie and TV Subtitles in multiple languages, thousands of translated subtitles uploaded daily. Free download from source, API support, millions of users.</description>
	<description lang="ms">Sarikata TV dan Movie dalam pelbagai bahasa, ribuan terjemahan sarikata dimuat-naik setiap hari.Muat-turun percuma dari sumber utama, sokongan API, jutaan pengguna.</description>
	<description lang="nl">Ondertitels voor films en tv-series in meerdere talen, dagelijks upload van duizenden vertaalde ondertitels. Gratis downloaden van de bron, API ondersteuning, miljoenen gebruikers.</description>
	<description lang="no">Undertekster for film og TV på mange språk, med tusener av nye oversettelser hver dag. Vi har gratis nedlasting av undertekster, API-support, og mange millioner brukere.</description>
	<description lang="pt-br">Milhares de legendas para filmes e seriados de TV, em vários idiomas, são traduzidas e enviadas diariamente. Download grátis, suporte API e milhões de usuários.</description>
	<description lang="pl">Napisy do filmów i seriali w wielu językach. Tysiące napisów dodawanych codziennie. Darmowe pobranie, miliony użytkowników.</description>
	<description lang="pt">Legendas de filmes e séries de TV em vários idiomas, milhares de legendas traduzidas e enviadas diariamente. Download grátis a partir da fonte, suporte API, milhões de utilizadores.</description>
	<description lang="ro">Subtitrari pentru filme in multe limbi, mii de subtitrari traduse si încărcate in fiecare zi. Descărca gratuit de la sursă, suport API, milioane de utilizatori.</description>
	<description lang="ru">Кино и ТВ субтитры на нескольких языках, тысячи переведенными субтитрами загружены ежедневно. Бесплатно скачать из исходных текстов, поддержка API, миллионы пользователей.</description>
	<description lang="sk">Titulky pre filmy a TV seriály, denne nahratých tisíce titulkov preložených vo viacerých jazykoch. Sťahuj zadarmo zo zdroja, podpora API, milióny používateľov.</description>
	<description lang="sl">Filmski in televizijski podnapisi v mnogo jezikih, na tisoče prevedenih podnapisov dnevno. Brezplačen prenos iz vira, podpora API, miljoni uporabnikov.</description>
	<description lang="sq">Titra filmash dhe serialesh në shumë gjuhë, mijëra titra të përkthyera që vendosen çdo ditë. Shkarko nga burimi, apo nga mbështetja e API-së, miliona përdorues.</description>
	<description lang="sr">Titlovi za filmove i TV na mnogim jezicima, hiljade prevoda okačenih svakodnevno. Besplatno skidanje sa izvora, podrška za API, milioni korisnika.</description>
	<description lang="sv">Filmer och Tv-undertexter med olika språk, tusentals översatta undertexter uppladdade dagligen. Gratis nerladdning från källor, API support, miljoner av användare.</description>
	<description lang="tr">Her gün eklenen, pek çok dildeki binlerce film ve dizi altyazısı. Kaynağından ücretsiz indirme, API desteği ve milyonlarca kullanıcı.</description>
	<description lang="uz">Film va TV Taglavhalari ko'p tillarda, minglab tarjima qilingan taglavhalar har kuni tizimga yuklanadi. Bepul resursdan yuklab oling, API qo'llaydi, millionlab foydalanuvchilar.</description>
	<description lang="zh">多语种的电影及剧集字幕，每日更新千余条翻译好的字幕。免费下载，提供API接口，已拥有上百万的用户。</description>
    <disclaimer>Users need to provide OpenSubtitles.org username and password in add-on configuration</disclaimer>
	<news>
v5.0.16 (2016-11-26) by opensubtitles
- Changed descriptions, icons, fanart... (by opensubtitles)

v5.0.15 (2016-11-26) by amet
- disable anonymous login, users need to register on opensubtitles.org and login in addon settings.
	</news>
    <platform>all</platform>
	<language></language>
    <license>GNU GENERAL PUBLIC LICENSE. Version 2, June 1991</license>
    <forum>https://forum.opensubtitles.org/viewtopic.php?f=8&amp;t=15847</forum>
    <website>http://www.opensubtitles.org</website>
    <email>admin [at] opensubtitles {dot} org</email>
	<assets>
	    <icon>resources/media/os_logo_512x512.png</icon>
	    <fanart>resources/media/os_fanart.jpg</fanart>
		<screenshot>resources/media/screenshot_1.jpg</screenshot>
		<screenshot>resources/media/screenshot_2.jpg</screenshot>
		<screenshot>resources/media/screenshot_3.jpg</screenshot>
	</assets>
    <source>https://github.com/opensubtitles/service.subtitles.opensubtitles</source>
  </extension>
</addon>

<addon id="service.subtitles.subscene"
       name="Subscene.com"
       version="1.7.1"
       provider-name="CrowleyAJ">
    <requires>
        <import addon="xbmc.python" version="2.14.0"/>
    </requires>
    <extension point="xbmc.subtitle.module"
               library="service.py"/>
    <extension point="xbmc.addon.metadata">
        <summary lang="en">Get subtitles from Subscene.com</summary>
        <description lang="en">Subscene.com provides subtitles in more than 50 languages, mainly in English, Arabic, Brazilian Portuguese, Farsi, Indonesian and Vietnamese.
Other languages with a great number of subtitles are: Danish, French, Swedish, Dutch, Italian, Norwegian and Spanish.</description>
        <disclaimer lang="en"/>
        <platform>all</platform>
        <language/>
        <license>GNU GENERAL PUBLIC LICENSE. Version 2, June 1991</license>
        <forum>http://forum.xbmc.org/showthread.php?tid=184854</forum>
        <website/>
        <email/>
        <source>https://github.com/manacker/service.subtitles.subscene</source>
    </extension>
</addon>

<addon id="service.subtitles.xshare" name="[COLOR red][B]xshare[/COLOR] [COLOR blue]subtitles[/B][/COLOR]" version="1.2.3" provider-name="thaitni">
    <requires><import addon="xbmc.python" version="2.1.0"/></requires>
    <extension point="xbmc.subtitle.module" library="xsharesub.py"/>
    <extension point="xbmc.addon.metadata">
        <platform>all</platform>
        <summary lang="en">xbmc subtitles for plugin.video.xshare</summary>
        <description lang="vi">Tìm phụ đề Tiếng Việt, tìm và dịch ra tiếng Việt từ bản tiếng Anh cho plugin.video.xshare trên http://Subscene.com, phudeviet.org.</description>
		<platform>all</platform>
		<language>en</language>
		<license>GNU General Public License - v2</license>
		<source>https://github.com/thaitni/xbmc.repo.xshare</source>
		<email>thai@thanhthai.net</email>
    </extension>
</addon>

<addon id="service.vietiptv"
       name="Viet IPTV Service"
       version="2.0"
       provider-name="Thanh Long">
  <requires>
    <import addon="xbmc.python" version="2.1.0"/>
  </requires>
  <extension point="xbmc.service" library="service.py" start="login" />
  <extension point="xbmc.addon.metadata">
    <platform>all</platform>
    <summary lang="en">Service to watching vietnamese channels from PVR Simple IPTV</summary>
	<description lang="en"></description>
	<website></website>
	<email>longprocimex@gmail.com</email>
  </extension>
</addon>

<addon id="service.vnmusic"
       name="Vn Music Service"
       version="1.0.2"
       provider-name="MrOdin">
  <requires>
    <import addon="xbmc.python" version="2.1.0"/>
    <import addon="script.module.requests" version="2.4.3"/>
  </requires>
  <extension point="xbmc.service" library="service.py" start="login" />
  <extension point="xbmc.addon.metadata">
    <platform>all</platform>
    <summary lang="en">Service support for vietnamese music addons (NhacCuaTui and Zing)</summary>
	<description lang="en"></description>
	<website></website>
	<email></email>
  </extension>
</addon>

<addon id="superrepo.kodi.isengard.all" name="SuperRepo All [Isengard][v7]" version="0.7.04" provider-name="Bart Otten">
                <requires>
                <import addon="xbmc.addon" version="12.0.0"/>
                </requires>
                <extension point="xbmc.addon.repository" name="SuperRepo All [Isengard][v7]">
                <info compressed="false">
                http://xml.superrepo.org/v7/.xml/isengard/all/addons.xml
                </info>
                <checksum>
                http://md5.superrepo.org/v7/.md5/isengard/all/addons.xml.md5
                </checksum>
                <datadir zip="true">http://redirect.superrepo.org/v7/addons/</datadir>
                <hashes>true</hashes>
                </extension>
                <extension point="xbmc.addon.metadata">
                <summary>
                Install add-ons from the SuperRepo All Repository
                </summary>
                <summary lang="nl">
                Installeer add-ons uit de SuperRepo All Repository
                </summary>
                <summary lang="cz">Inštalácia add-ons zo SuperRepo All Repozitár</summary>
                <summary lang="de">
                Installation von Addons aus dem SuperRepo All Repository
                </summary>
                <summary lang="pt">Instale add-ons do SuperRepo All Repositório</summary>
                <summary lang="br">Instale add-ons do SuperRepo All Repositório</summary>
                <description>
                Download and install add-ons for Kodi in the category "All" using SuperRepo.[CR][CR]By using SuperRepo repositories you will be able to take advantage of our serverside dependency checking, extensive file mirror service and many more.[CR]Visit our website at https://superrepo.org/ to browse the add-ons, create personal addon bundles and install whole bundles at once![CR][CR]
                </description>
                <description lang="nl">
                Download and installeer add-ons voor Kodi in de categorie "All" via SuperRepo.[CR]Door SuperRepo te installeren kunt u profiteren van onze controle van add-ons en ons uitgebreide server netwerk. Bezoek onze website op https://superrepo.org om door de add-ons te bladeren, persoonlijke add-on bundels te maken en complete bundels in 1 keer te installeren![CR][CR]
                </description>
                <description lang="cz">
                Preber a inštaluj add-ons do kategórie "All" z SuperRepo.org add-on repozitár.[CR][CR]Ak si našiel add-on ktorý je poškodený alebo nefunkčný, alebo chceš pridať nový add-on, potom prosím pozri na https://superrepo.org/[CR][CR]Repozitár je udržiavaný komunitou Kodi a za pomoci SuperRepo Wiki, a tento preberá add-ons z rôznych zdrojov. Vzhľadom na to, SuperRepo nenesie žiadnu zodpovednosť za služby poskytované týmito add-ons.[CR][CR]Rozšírený repozitár vyvinul Bart Otten[CR][CR]
                </description>
                <description lang="de">
                Lade und installiere Addons der Kategorie "All" aus dem SuperRepo.org Addon Repository.[CR][CR]Möchtest du ein fehlerhaftes Addon melden oder ein neues Addon vorschlagen, kannst du dies über unsere Webseite http://superrepo.org tun.[CR][CR]Das Repository wird mit Hilfe des SuperRepo Wiki durch die Kodi Community gepflegt und durch unseren Generator aus mehreren Quellen zusammengestellt. Daher übernimmt SuperRepo keinerlei Verantwortung für diesen Service.[CR][CR]Der"eXtended Reposity Generator" wird durch Bart Otten entwickelt.[CR][CR]
                </description>
                <description lang="pt">
                Baixe e instale o add-ons na categoria "All" do Repositório SuperRepo.org. [CR] [CR] Se você encontrar um add-on quebrado ou não funcionando, ou você gostaria de incluir um outro, por favor visite https://superrepo.org/ [CR] [CR]O repositório é mantida pela comunidade do Kodi usando o Wiki do SuperRepo e o nosso gerador de busca de add-ons múltiplas fontes. Portanto SuperRepo não aceita qualquer responsabilidade por esse serviço.[CR][CR]O Gerador Reposity eXtended é desenvolvido por Bart Otten[CR][CR]
                </description>
                <description lang="br">
                Baixe e instale o add-ons na categoria "All" do Repositório SuperRepo.org. [CR] [CR] Se você encontrar um add-on quebrado ou não funcionando, ou você gostaria de incluir um outro, por favor visite https://superrepo.org/ [CR][CR]O repositório é mantida pela comunidade do Kodi usando o Wiki do SuperRepo e o nosso gerador de busca de add-ons múltiplas fontes. Portanto SuperRepo não aceita qualquer responsabilidade por esse serviço.[CR][CR]O Gerador Reposity eXtended é desenvolvido por Bart Otten[CR][CR]
                </description>
                <disclaimer>
                The SuperRepo generator fetches addons from multiple sources. Therefore SuperRepo accepts no responsibility for included addons.[CR]
                </disclaimer>
                <disclaimer lang="nl">
                De SuperRepo generator verzamelt addons van verschillende bronnen. Daarom accepteert SuperRepo geen enkele verantwoordelijkheid voor de ingevoegde addons.[CR]
                </disclaimer>
                <disclaimer lang="cz">
                Repozitár je udržiavaný komunitou Kodi a za pomoci SuperRepo Wiki, a tento preberá addons z rôznych zdrojov. Vzhľadom na to, SuperRepo nenesie žiadnu zodpovednosť za služby poskytované týmito addons.[CR]
                </disclaimer>
                <disclaimer lang="de">
                Das Repository wird durch die Kodi Community gepflegt und durch unseren Generator aus mehreren Quellen zusammengestellt. Daher übernimmt SuperRepo keinerlei Verantwortung für die enthaltenen Addons.[CR]
                </disclaimer>
                <disclaimer lang="pt">
                O repositório é mantido pela comunidade comunidade do Kodi e o nosso gerador de busca de addons de múltiplas fontes. Portanto SuperRepo aceita não se responsabiliza por addons incluídos.[CR]
                </disclaimer>
                <disclaimer lang="br">
                O repositório é mantido pela comunidade comunidade do Kodi e o nosso gerador de busca de addons de múltiplas fontes. Portanto SuperRepo aceita não se responsabiliza por addons incluídos.[CR]
                </disclaimer>
                <platform>all</platform>
                <website>https://superrepo.org/</website>
                </extension>
                </addon>

<addon id="xbmc.repo.xshare" name="Xshare Repository" version="1.0.0" provider-name="thaitni">
	<extension point="xbmc.addon.repository" name="Official XBMC.org Add-on Repository">
		<info compressed="true">https://raw.githubusercontent.com/thaitni/xbmc.repo.xshare/master/addons.xml</info>
		<checksum>https://raw.githubusercontent.com/thaitni/xbmc.repo.xshare/master/addons.xml.md5</checksum>
		<datadir zip="true">https://raw.githubusercontent.com/thaitni/xbmc.repo.xshare/master</datadir>
		<hashes>true</hashes>
	</extension>
	<extension point="xbmc.addon.metadata">
		<summary>Play Video with find subs on XBMC from many host</summary>
		<description>Download and install addons from Xshare Repository: Watch movies from fshare.vn, 4share.vn, tenlua.vn, ...</description>
		<language>en</language>
		<platform>all</platform>
		<license>GNU General Public License - v2</license>
		<source>https://github.com/thaitni/xbmc.repo.xshare</source>
		<email>thai@thanhthai.net</email>
	</extension>
</addon>
</addons>
