# Technical Specifications

{% tabs %}
{% tab title="Denominations" %}
| Denominations |  |
| :--- | :--- |
| Plural | DigiBytes |
| Ticker symbol | DGB |
| Currency symbol | Ɗ \(Unicode: [U+018A](https://unicode-table.com/en/018A/)\) |
| Precision | 10⁻⁸ |
{% endtab %}

{% tab title="Subunits" %}
| Subunits |  |
| :--- | :--- |
| mDGB \(miliDigibyte\) | 1/1000 |
| µDGB \(microDigibyte\) | 1/1000000 |
| ɗSats \(digiSatoshi, Digis | 1/100000000 |
{% endtab %}

{% tab title="Development" %}
<table>
  <thead>
    <tr>
      <th style="text-align:left">Development</th>
      <th style="text-align:left"></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left">Original author(s)</td>
      <td style="text-align:left">Jared Tate</td>
    </tr>
    <tr>
      <td style="text-align:left">White Paper</td>
      <td style="text-align:left"><a href="https://digibyte.io/docs/infopaper.pdf">&quot;DigiByte community info paper&quot;</a>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">Implementation(s)</td>
      <td style="text-align:left">
        <p><a href="https://github.com/digibyte-core/digibyte/releases/">DigiByte Protocol</a> (Github
          releases)</p>
        <p><a href="https://github.com/digibyte-core">DigiByte Core</a> (Github projects
          and repositories)</p>
        <p><a href="https://github.com/digibyte-core/DigiAssets-Protocol-Specifications/wiki">DigiAssets Protocol Specifications</a> (Github
          wiki)</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">Initial release</td>
      <td style="text-align:left">1.0 / 10 January 2014</td>
    </tr>
    <tr>
      <td style="text-align:left">Latest release</td>
      <td style="text-align:left"><a href="https://github.com/digibyte/digibyte/releases/tag/v7.17.2">7.17.2</a> /
        3 May 2019</td>
    </tr>
    <tr>
      <td style="text-align:left">Development status</td>
      <td style="text-align:left">Active</td>
    </tr>
    <tr>
      <td style="text-align:left">Deployment status</td>
      <td style="text-align:left">Deployed (Working Product)</td>
    </tr>
  </tbody>
</table>
{% endtab %}

{% tab title="Ledger" %}
| Ledger |  |
| :--- | :--- |
| Ledger start | 10 January 2014 |
| Genesis block hash | ["USA Today: 10/Jan/2014, Target: Data stolen from​ up to 110M customers"](https://github.com/digibyte/digibyte/blob/master/src/chainparams.cpp#L52) |
| Ledger type | Public, Decentralized, UTXO based, Multi-Algorithm |
| [Timestamping scheme](https://en.wikipedia.org/wiki/Trusted_timestamping) | [Proof-of-work](https://en.wikipedia.org/wiki/Proof-of-work_system) \(Partial hash inversion\) |
| Issuance shedule | Decentralized \(block reward\) Initially Ɗ72,000 per block, 1% reduced every month. |
| Block reward | 543DGB \(Jan 2021\) |
| Block time | 15 seconds, \(75 seconds per Algorithm\) |
| Algorithm block share | 20% Block Share per Algorithm\(5 Algorithms x 20% for total Block Share\) |
| Difficulty retarget | Every 1 Block, 5 Separate Difficulties, 1 For each Mining Algo |
| Block size and capacity | Max block size 1MB. [1066 TPS with 4x SegWit scaling](https://www.dgbwiki.com/index.php?title=DigiSpeed) |
| Block explorer | [digiexplorer.info](https://digiexplorer.info/) [chainz.cryptoid.info](https://chainz.cryptoid.info/dgb/) [ccore.online](https://dgb.ccore.online/) [more...](https://www.dgbwiki.com/index.php?title=DigiByte_Explorers) |
| Circulating supply | Ɗ13,898,145,957 \(January 2021\) |
| Supply limit | Ɗ21,000,000,000 \(Supply limit reached in 2035\) |
| Address formats | ["D" prefixed legacy addresses "S" prefixed p2sh SegWit compatible / MultiSig addresses "dgb1" prefixed bech32 native Segwit addresses](https://medium.com/@josiah_digibyte/technical-new-address-formats-and-rpc-calls-c1119317a76c) |
| SegWit support | [Yes. First major Altcoin to successfully activate SegWit. \(April 2017\)](https://twitter.com/digibytecoin/status/857995712843448320) |
| 6x Hard forks | [DigiShield](https://www.dgbwiki.com/index.php?title=DigiShield) [MultiAlgo](https://www.dgbwiki.com/index.php?title=MultiAlgo) [MultiShield](https://www.dgbwiki.com/index.php?title=MultiShield) [DigiSpeed](https://www.dgbwiki.com/index.php?title=DigiSpeed) [DigiSync](https://www.dgbwiki.com/index.php?title=DigiSync) [Odocrypt](https://www.dgbwiki.com/index.php?title=Odocrypt) |
| 4x Soft forks | [CSV](https://www.dgbwiki.com/index.php?title=CSV) [NVersionBits](https://www.dgbwiki.com/index.php?title=NVersionBits) [SegWit](https://twitter.com/digibytecoin/status/857995712843448320) [ReserveAlgo](https://github.com/digibyte/digibyte/releases/tag/v6.17.2) |
{% endtab %}
{% endtabs %}



