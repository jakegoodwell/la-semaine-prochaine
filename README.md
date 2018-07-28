# la-semaine-prochaine
	<a href="javascript:switchtohttps()" title="Click to view the same content over https." style="color:red;">Switch to https://</a>
					<script type="text/javascript">
					function switchtohttps(){
						if (window.location.protocol != "https:"){
							window.location.href = "https:" + window.location.href.substring(window.location.protocol.length);
						}
					}
					</script>
							<a href="/index.php" title="Home page">Home</a>
				<b>Browse :</b><br/>
				<a href="/vendor.php" title="Browse software and hardware vendors">Vendors</a>
				<a href="/product-list.php" title="Browse software and hardware products">Products</a>
				<a href="/browse-by-date.php" title="Browse security vulnerabilities by date">Vulnerabilities By Date</a>
				<a href="/vulnerabilities-by-types.php" title="Vulnerability distribution by type">Vulnerabilities By Type</a>
				<b>Reports :</b><br/>
				<a href="/cvss-score-charts.php" title="CVSS score distribution report">CVSS Score Report</a>
				<a href="/cvss-score-distribution.php" title="CVSS score distribution for all vulnerabilities">CVSS Score Distribution</a>
				<b>Search :</b><br/>
				<a href="/vendor-search.php" title="Search for software and hardware vendors">Vendor Search</a>
				<a href="/product-search.php" title="Search for software and hardware products">Product Search</a>
				<a href="/version-search.php" title="Fast search by vendor, product and version">Version Search</a>
								<a href="/vulnerability-search.php" title="(Really) Advanced search for security vulnerabilities">Vulnerability Search</a>
				<a href="/search-by-microsoft-refid.php" title="Search For Vulnerabilities By Microsoft References">By Microsoft References</a>
				<b>Top 50 :</b><br/>
				<a href="/top-50-vendors.php" title="Top 50 vendors having highest number of security vulnerabilities">Vendors</a>
				<a href="/top-50-vendor-cvssscore-distribution.php" title="Cvss score distribution for top 50 vendors">Vendor Cvss Scores</a>
				<a href="/top-50-products.php" title="Top 50 products having highest number of security vulnerabilities">Products</a>
				<a href="/top-50-product-cvssscore-distribution.php" title="Cvss score distribution for top 50 products">Product Cvss Scores</a>
				<a href="/top-50-versions.php" title="Top 50 versions of products having highest number of security vulnerabilities related to them">Versions</a>
				<b>Other :</b><br/>
				<a href="/microsoft-bulletins.php" title="Microsoft security bulletins">Microsoft Bulletins</a>
				<a href="/bugtraq-list/" title="Bugtraq entries">Bugtraq Entries</a>
				<a href="/cwe-definitions.php" title="Browse CWE Definitions">CWE Definitions</a>
				<a href="/about-contact.php" title="About cvedetails.com">About &amp; Contact</a>
				<a title="Uservoice forum" href="http://cvedetails.uservoice.com">Feedback</a>
				<a title="Help topics and more information about CVE" href="/cve-help.php">CVE Help</a>
				<a title="Frequently asked questions" href="/faq.php">FAQ</a>
				<a title="Articles" href="/article.php">Articles</a>
				<b>External Links :</b><br/>
				<a href="http://nvd.nist.gov" title="National vulnerability database web site - External link " target="_blank">NVD Website</a>
				<a href="http://cwe.mitre.org/" title="Common weakness enumeration at mitre.org - External link " target="_blank">CWE Web Site</a>
			</div>

			<form action="/cve-details.php" method="get">
			<table class="menuformtable">
				<tr>
					<th>View CVE :</th>
				</tr>
				<tr>
					<td>
						<input type="text"  name="cve_id" value="" size="10" maxlength="15">
						<input type="submit" value="Go">
					</td>
				</tr>
				<tr>
					<td>
					(e.g.: CVE-2009-1234 or 2010-1234 or 20101234)
					</td>
				</tr>
			</table>
			</form>
