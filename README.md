<h1 id="strawberry">strawberry</h1>

<p>A pink vim theme.</p>

<h2 id="screenshots">screenshots</h2>

<table>
<tr><td align="center"><strong>strawberry-dark</strong></td><td align="center"><strong>strawberry-light</strong></td></tr>
<tr>
<td><img src="/img/screenshot-strawberry-dark.png" alt="screenshot of the strawberry-dark vim theme" width="288" /></td>
<td align="center"><img src="/img/screenshot-strawberry-light.png" alt="screenshot of the strawberry-light vim theme" width="288" /></td>
</tr>
</table>

<blockquote>
  <p>pictured font: <a href="http://input.fontbureau.com/">Input Mono</a></p>
</blockquote>

<h2 id="setup">setup</h2>

<h3 id="installation">installation</h3>

<p>While vim themes can be installed manually (place <a href="https://github.com/nightsense/strawberry/tree/master/colors">theme file</a> in <code class="highlighter-rouge">~/.vim/colors/</code>), a <strong>plugin helper</strong> is recommended.</p>

<p>If you don’t have a preferred helper, consider trying <a href="https://github.com/junegunn/vim-plug">vim-plug</a>, which can be installed with:</p>

<div class="highlighter-rouge"><pre class="highlight"><code>curl -fLo ~/.vim/autoload/plug.vim --create-dirs \
    https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim
</code></pre>
</div>

<p>To install strawberry via vim-plug, add the following to the top of your <code class="highlighter-rouge">vimrc</code>:</p>

<div class="highlighter-rouge"><pre class="highlight"><code>call plug#begin('~/.vim/plugged')
Plug 'nightsense/strawberry'
call plug#end()
</code></pre>
</div>

<p>Then restart vim and run <code class="highlighter-rouge">PlugUpdate</code> (from the vim command line).</p>

<h3 id="activation">activation</h3>

<p>To activate the strawberry theme, add one of the following lines to your <code class="highlighter-rouge">vimrc</code>:</p>

<ul>
  <li><code class="highlighter-rouge">colorscheme strawberry-light</code></li>
  <li><code class="highlighter-rouge">colorscheme strawberry-dark</code></li>
</ul>

<p>Note that the <code class="highlighter-rouge">background</code> setting doesn’t affect this theme.</p>

<blockquote>
  <p>To assign themes to specific intervals of the day, try the <a href="https://github.com/nightsense/night-and-day">night-and-day</a> plugin.</p>
</blockquote>

<h2 id="terminal-vim">terminal vim</h2>

<p>See the <a href="https://github.com/nightsense/nightshell">nightshell</a> repository, which allows strawberry to be used in a variety of terminal applications.</p>

<h2 id="palette">palette</h2>

<p>strawberry consists of 16 colours:</p>

<ul>
  <li>8 theme-distinct <strong>base colours</strong></li>
  <li>8 standard <strong>accent colours</strong> (shared by members of the “nightsense theme family”) for syntax highlighting
    <ul>
      <li>hues were selected at the scale of 1/12 (30°) colour wheel intervals, followed by 1/12 subinterval adjustments</li>
      <li>value and saturation were tuned for light backgrounds, then lowered for dark backgrounds</li>
    </ul>
  </li>
  <li>all text/background contrast ratios meet the 3:1 <a href="https://www.w3.org/TR/UNDERSTANDING-WCAG20/visual-audio-contrast-contrast.html#visual-audio-contrast-contrast-73-head">ISO standard</a></li>
</ul>

<table>
  <thead>
    <tr>
      <th style="text-align: right">base</th>
      <th style="text-align: center">light-background accents</th>
      <th style="text-align: left">dark-background accents</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align: right"><img src="http://www.colorhexa.com/2b191e.png" height="24" width="42" /> <code class="highlighter-rouge">2b191e</code> </td>
      <td style="text-align: center"><img src="http://www.colorhexa.com/eb3a3a.png" height="24" width="42" /> <code class="highlighter-rouge">eb3a3a</code> </td>
      <td style="text-align: left"><img src="http://www.colorhexa.com/e05f5f.png" height="24" width="42" /> <code class="highlighter-rouge">e05f5f</code></td>
    </tr>
    <tr>
      <td style="text-align: right"><img src="http://www.colorhexa.com/40252d.png" height="24" width="42" /> <code class="highlighter-rouge">40252d</code> </td>
      <td style="text-align: center"><img src="http://www.colorhexa.com/e06812.png" height="24" width="42" /> <code class="highlighter-rouge">e06812</code> </td>
      <td style="text-align: left"><img src="http://www.colorhexa.com/d48146.png" height="24" width="42" /> <code class="highlighter-rouge">d48146</code></td>
    </tr>
    <tr>
      <td style="text-align: right"><img src="http://www.colorhexa.com/54313b.png" height="24" width="42" /> <code class="highlighter-rouge">54313b</code> </td>
      <td style="text-align: center"><img src="http://www.colorhexa.com/c9af42.png" height="24" width="42" /> <code class="highlighter-rouge">c9af42</code> </td>
      <td style="text-align: left"><img src="http://www.colorhexa.com/bda84f.png" height="24" width="42" /> <code class="highlighter-rouge">bda84f</code></td>
    </tr>
    <tr>
      <td style="text-align: right"><img src="http://www.colorhexa.com/754f5a.png" height="24" width="42" /> <code class="highlighter-rouge">754f5a</code> </td>
      <td style="text-align: center"><img src="http://www.colorhexa.com/25942e.png" height="24" width="42" /> <code class="highlighter-rouge">25942e</code> </td>
      <td style="text-align: left"><img src="http://www.colorhexa.com/639467.png" height="24" width="42" /> <code class="highlighter-rouge">639467</code></td>
    </tr>
    <tr>
      <td style="text-align: right"><img src="http://www.colorhexa.com/946372.png" height="24" width="42" /> <code class="highlighter-rouge">946372</code> </td>
      <td style="text-align: center"><img src="http://www.colorhexa.com/0c9489.png" height="24" width="42" /> <code class="highlighter-rouge">0c9489</code> </td>
      <td style="text-align: left"><img src="http://www.colorhexa.com/4a948e.png" height="24" width="42" /> <code class="highlighter-rouge">4a948e</code></td>
    </tr>
    <tr>
      <td style="text-align: right"><img src="http://www.colorhexa.com/bf8093.png" height="24" width="42" /> <code class="highlighter-rouge">bf8093</code> </td>
      <td style="text-align: center"><img src="http://www.colorhexa.com/3083bf.png" height="24" width="42" /> <code class="highlighter-rouge">3083bf</code> </td>
      <td style="text-align: left"><img src="http://www.colorhexa.com/6097bf.png" height="24" width="42" /> <code class="highlighter-rouge">6097bf</code></td>
    </tr>
    <tr>
      <td style="text-align: right"><img src="http://www.colorhexa.com/e0bac6.png" height="24" width="42" /> <code class="highlighter-rouge">e0bac6</code> </td>
      <td style="text-align: center"><img src="http://www.colorhexa.com/8760bf.png" height="24" width="42" /> <code class="highlighter-rouge">8760bf</code> </td>
      <td style="text-align: left"><img src="http://www.colorhexa.com/9a80bf.png" height="24" width="42" /> <code class="highlighter-rouge">9a80bf</code></td>
    </tr>
    <tr>
      <td style="text-align: right"><img src="http://www.colorhexa.com/ffebf1.png" height="24" width="42" /> <code class="highlighter-rouge">ffebf1</code> </td>
      <td style="text-align: center"><img src="http://www.colorhexa.com/e05e85.png" height="24" width="42" /> <code class="highlighter-rouge">e05e85</code> </td>
      <td style="text-align: left"><img src="http://www.colorhexa.com/d47b95.png" height="24" width="42" /> <code class="highlighter-rouge">d47b95</code></td>
    </tr>
  </tbody>
</table>

<p><img src="http://www.colorhexa.com/eb3a3a.png" height="24" width="42" />
<strong>Red</strong>, the colour of alarm, is used for <strong>warning elements</strong>, including error messages, misspellings, and diff deletions.</p>

<p><img src="http://www.colorhexa.com/e06812.png" height="24" width="42" />
<strong>Orange</strong> is the colour of fire, which serves as a preliminary to many practical activities. Orange is therefore used for <strong>preliminary elements</strong>, such as preprocessor commands (which prepare data to be handled by another program), incremental searching (that is, a search term in the process of being typed), titles, and miscapitalized words.</p>

<p><img src="http://www.colorhexa.com/c9af42.png" height="24" width="42" />
<strong>Yellow</strong>, the classic highlighting colour, is applied to elements that are not warnings yet should draw attention with high visibility. These <strong>highlighted elements</strong> include search results, task tags (<code class="highlighter-rouge">TODO</code>, <code class="highlighter-rouge">FIXME</code>…), and diff changes.</p>

<p><img src="http://www.colorhexa.com/25942e.png" height="24" width="42" />
<strong>Green</strong>, the colour that says “go ahead, proceed with the task at hand”, is used for <strong>action elements</strong>, such as statements (if/then, while/do, case…), mode indicators (insert, visual…), vim user prompts, and diff additions.</p>

<p><img src="http://www.colorhexa.com/0c9489.png" height="24" width="42" />
<strong>Teal</strong> is named after the “common teal”, a kind of duck, thus connecting this colour with the concept of “species”, which is a means of classifying life into very specific types. Teal is therefore used for specifying <strong>object types</strong>, such as data type (boolean, integer, string…) or storage class (static, volatile…), as well as mislocalized words (that is, words that are not misspelled but of the wrong type, namely a foreign locale type).</p>

<p><img src="http://www.colorhexa.com/3083bf.png" height="24" width="42" />
<strong>Blue</strong>, a colour of calm stability, is used for <strong>constants</strong>, which come in the form of boolean values, integers, floating-point numbers, characters, and strings.</p>

<p><img src="http://www.colorhexa.com/8760bf.png" height="24" width="42" />
<strong>Purple</strong>, often associated with rare purple dyes historically produced for special works of art, is used for <strong>special text</strong>, including special characters (standalone or within syntax units), vim tags, and debugging statements. Rarely-used words are also marked, allowing the writer to consider whether such a specially uncommon word is appropriate.</p>

<p><img src="http://www.colorhexa.com/e05e85.png" height="24" width="42" />
<strong>Pink</strong>, the colour of spring blossoms, is used for <strong>object names</strong>, including the names of variables and functions. To code is to bring countless objects blossoming into existence as one types their names.</p>
