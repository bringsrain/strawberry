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
  <p>pictured font: <a href="http://input.fontbureau.com/">Input Mono Narrow</a> (1.2x line spacing)</p>
</blockquote>

<h2 id="setup">setup</h2>

<h3 id="installation">installation</h3>

<p>While vim themes can be installed manually (place <a href="https://github.com/nightsense/strawberry/tree/master/colors">theme file</a> in <code class="highlighter-rouge">~/.vim/colors/</code>), a <strong>plugin helper</strong> is recommended.</p>

<p>If you don’t have a preferred helper, consider trying <a href="https://github.com/junegunn/vim-plug">vim-plug</a>, which can be installed with:</p>

<div class="highlighter-rouge"><pre class="highlight"><code>curl -fLo ~/.vim/autoload/plug.vim --create-dirs \
  https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim
</code></pre>
</div>

<p>To install strawberry using vim-plug, add the following to the top of your <code class="highlighter-rouge">vimrc</code>:</p>

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

<blockquote>
  <p>To assign themes to specific intervals of the day, try the <a href="https://github.com/nightsense/night-and-day">night-and-day</a> plugin.</p>
</blockquote>

<h2 id="terminal-vim">terminal vim</h2>

<p>See the <a href="https://github.com/nightsense/nightshell">nightshell</a> repository, which allows strawberry to be used in a variety of terminal applications.</p>

<h2 id="palette">palette</h2>

<p>strawberry consists of 8 theme-distinct <strong>base colours</strong>, which are used for most interface elements, and 8 standard <strong>accent colours</strong> (common to the “nightsense theme family”) used for syntax highlighting.</p>

<blockquote>
  <ul>
    <li>accent colour hues were selected at the scale of 1/12 (30°) colour wheel intervals, followed by 1/6 subinterval adjustments</li>
    <li>base colour hue was selected from among:
      <ul>
        <li>the 24 hues available at the scale of 1/24 (15°) colour wheel intervals</li>
        <li>the additional fine-tuned accent hues</li>
      </ul>
    </li>
    <li>discrete intervals were also used for tuning colour saturations (1/24) and values (1/12)</li>
    <li>the <a href="https://www.w3.org/TR/UNDERSTANDING-WCAG20/visual-audio-contrast-contrast.html#visual-audio-contrast-contrast-73-head">ISO 3:1 contrast standard</a> is met by nearly all text/background combinations, exceptions being made for some transient-highlighted backgrounds (e.g. cursorcolumn, cursorline)</li>
  </ul>
</blockquote>

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
      <td style="text-align: right"><img src="http://www.colorhexa.com/2b121f.png" height="24" width="42" /> <code class="highlighter-rouge">2b121f</code> </td>
      <td style="text-align: center"><img src="http://www.colorhexa.com/eb493a.png" height="24" width="42" /> <code class="highlighter-rouge">eb493a</code> </td>
      <td style="text-align: left"><img src="http://www.colorhexa.com/eb7f75.png" height="24" width="42" /> <code class="highlighter-rouge">eb7f75</code></td>
    </tr>
    <tr>
      <td style="text-align: right"><img src="http://www.colorhexa.com/402532.png" height="24" width="42" /> <code class="highlighter-rouge">402532</code> </td>
      <td style="text-align: center"><img src="http://www.colorhexa.com/e06812.png" height="24" width="42" /> <code class="highlighter-rouge">e06812</code> </td>
      <td style="text-align: left"><img src="http://www.colorhexa.com/e0894a.png" height="24" width="42" /> <code class="highlighter-rouge">e0894a</code></td>
    </tr>
    <tr>
      <td style="text-align: right"><img src="http://www.colorhexa.com/543846.png" height="24" width="42" /> <code class="highlighter-rouge">543846</code> </td>
      <td style="text-align: center"><img src="http://www.colorhexa.com/e0c438.png" height="24" width="42" /> <code class="highlighter-rouge">e0c438</code> </td>
      <td style="text-align: left"><img src="http://www.colorhexa.com/c9b755.png" height="24" width="42" /> <code class="highlighter-rouge">c9b755</code></td>
    </tr>
    <tr>
      <td style="text-align: right"><img src="http://www.colorhexa.com/75616b.png" height="24" width="42" /> <code class="highlighter-rouge">75616b</code> </td>
      <td style="text-align: center"><img src="http://www.colorhexa.com/349e3d.png" height="24" width="42" /> <code class="highlighter-rouge">349e3d</code> </td>
      <td style="text-align: left"><img src="http://www.colorhexa.com/5c9e61.png" height="24" width="42" /> <code class="highlighter-rouge">5c9e61</code></td>
    </tr>
    <tr>
      <td style="text-align: right"><img src="http://www.colorhexa.com/947b87.png" height="24" width="42" /> <code class="highlighter-rouge">947b87</code> </td>
      <td style="text-align: center"><img src="http://www.colorhexa.com/289e8b.png" height="24" width="42" /> <code class="highlighter-rouge">289e8b</code> </td>
      <td style="text-align: left"><img src="http://www.colorhexa.com/4f9e91.png" height="24" width="42" /> <code class="highlighter-rouge">4f9e91</code></td>
    </tr>
    <tr>
      <td style="text-align: right"><img src="http://www.colorhexa.com/bf9faf.png" height="24" width="42" /> <code class="highlighter-rouge">bf9faf</code> </td>
      <td style="text-align: center"><img src="http://www.colorhexa.com/3f8abf.png" height="24" width="42" /> <code class="highlighter-rouge">3f8abf</code> </td>
      <td style="text-align: left"><img src="http://www.colorhexa.com/6f9ebf.png" height="24" width="42" /> <code class="highlighter-rouge">6f9ebf</code></td>
    </tr>
    <tr>
      <td style="text-align: right"><img src="http://www.colorhexa.com/e0c5d3.png" height="24" width="42" /> <code class="highlighter-rouge">e0c5d3</code> </td>
      <td style="text-align: center"><img src="http://www.colorhexa.com/975bb5.png" height="24" width="42" /> <code class="highlighter-rouge">975bb5</code> </td>
      <td style="text-align: left"><img src="http://www.colorhexa.com/a688b5.png" height="24" width="42" /> <code class="highlighter-rouge">a688b5</code></td>
    </tr>
    <tr>
      <td style="text-align: right"><img src="http://www.colorhexa.com/ffebf5.png" height="24" width="42" /> <code class="highlighter-rouge">ffebf5</code> </td>
      <td style="text-align: center"><img src="http://www.colorhexa.com/c96587.png" height="24" width="42" /> <code class="highlighter-rouge">c96587</code> </td>
      <td style="text-align: left"><img src="http://www.colorhexa.com/c997a8.png" height="24" width="42" /> <code class="highlighter-rouge">c997a8</code></td>
    </tr>
  </tbody>
</table>

<p><img src="http://www.colorhexa.com/eb493a.png" height="24" width="42" />
<strong>Red</strong>, the colour of alarm, is used for <strong>warning elements</strong>, including error messages, misspellings, and diff deletions.</p>

<p><img src="http://www.colorhexa.com/e06812.png" height="24" width="42" />
<strong>Orange</strong>, the colour of fire, can be associated with the preliminary “warmup” phase of some activity; literally, this could be the heating-up of a hearth for forging, or a stove for cooking. Orange is therefore used for <strong>preliminary elements</strong>, such as preprocessor commands (which prepare data to be handled by another program), incremental searching (that is, a search term in the process of being typed), titles, and miscapitalized words.</p>

<p><img src="http://www.colorhexa.com/e0c438.png" height="24" width="42" />
<strong>Yellow</strong>, the classic highlighting colour, is applied to elements that are not warnings, yet should draw attention with high visibility. These <strong>highlighted elements</strong> include search results, task tags (<code class="highlighter-rouge">TODO</code>, <code class="highlighter-rouge">FIXME</code>…), and diff changes.</p>

<p><img src="http://www.colorhexa.com/349e3d.png" height="24" width="42" />
<strong>Green</strong>, the colour that says “go ahead, proceed with the task at hand”, is used for <strong>action elements</strong>, such as statements (if/then, while/do, case…), mode indicators (insert, visual…), vim user prompts, and diff additions.</p>

<p><img src="http://www.colorhexa.com/289e8b.png" height="24" width="42" />
<strong>Teal</strong> is named after the “common teal”, a kind of duck, thus connecting this colour with the concept of “species”, which is a means of classifying life into very specific types. Teal is therefore used for specifying <strong>object types</strong>, such as data type (boolean, integer, string…) or storage class (static, volatile…), as well as marking mislocalized words (that is, words that are not misspelled but of the wrong type, namely a foreign locale type).</p>

<p><img src="http://www.colorhexa.com/3f8abf.png" height="24" width="42" />
<strong>Blue</strong>, a colour of calm stability, is used for <strong>constants</strong>, which come in the form of boolean values, integers, floating-point numbers, characters, and strings.</p>

<p><img src="http://www.colorhexa.com/975bb5.png" height="24" width="42" />
<strong>Purple</strong>, often associated with (historically) rare purple dyes produced for special works of art, is used for <strong>special text</strong>, including special characters (standalone or within syntax units), vim tags, and debugging statements. Rarely-used words are also marked, allowing the writer to consider whether such a specially uncommon word is appropriate.</p>

<p><img src="http://www.colorhexa.com/c96587.png" height="24" width="42" />
<strong>Pink</strong>, the colour of spring blossoms, is used for <strong>object names</strong>, including the names of variables and functions. To code is to bring countless objects blossoming into life as one types their names.</p>
