.. _formatting-messages:

Formatting Messages
===================

For the most part, you write messages in plain text without special formatting. However, Mattermost supports a type of text markup called *Markdown*. With Markdown, you can embellish your messages with bold text, italic text, emojis, headings, lists, and the like.

To create these effects, you type control characters such as asterisks, underscores, and colons. For example, to emphasize a word with italics, surround it with either an asterisk or an underscore on each side. To create bold text, use a pair of asterisks or underscores.

The following table shows a few basic effects. For the complete list, see :doc:`ref-message-text-format`.

.. raw:: html

  <table width="100%" border="1" cellpadding="5px" style="margin-bottom:20px;">
    <tr class="row-odd">
      <th class="head">Formatted message that you type</th>
      <th class="head">Output</th>
    </tr>
    <tr class="row-odd">
      <td valign="middle">You can use asterisks to make *italic text*, or you can use the underscore, like this: _italic text_.</td>
      <td valign="middle">You can use asterisks to make <i>italic text</i>, or you can use the underscore, like this: <i>italic text</i>.</td>
    </tr>
    <tr class="row-odd">
      <td valign="middle">To make bold text, use two asterisks or underscores, **like this** or __like this__.</td>
      <td valign="middle">To make bold text, use two asterisks or underscores, <b>like this</b> or <b>like this</b>.</td>
    </tr>
    <tr class="row-odd">
      <td valign="middle">To add an emoji such as a :smiley:, type a colon, the name of an emoji, then another colon.</td>
      <td valign="middle">To add an emoji such as a <img src="../_images/smiley.png">, type a colon, the name of an emoji, then another colon.</td>
    </tr>
    <tr class="row-odd">
      <td valign="middle">You can also use asterisks to create a bullet list:
        <ul style="margin-bottom: 5px;">
          <li style="list-style: none;">* Item one in the list.</li>
          <li style="list-style: none;">* The second item in the list.</li>
          <li style="list-style: none;">* This is the third item.</li>
        </ul>
      </td>
      <td valign="middle">
        <ul style="margin-bottom: 5px;">
          <li>Item one in the list.</li>
          <li>The second item in the list.</li>
          <li>This is the third item.</li>
        </ul>
      </td>
    </tr>
    <tr class="row-odd">
      <td valign="middle">Use numbers to make a numbered list:
        <ul style="margin-bottom: 5px;">
          <li style="list-style: none;">1. Item one in the list.</li>
          <li style="list-style: none;">1. The second item in the list.</li>
          <li style="list-style: none;">1. This is the third item.</li>
        </ul>
      </td>
      <td valign="middle">
        <ol>
          <li>Item one in the list.</li>
          <li>The second item in the list.</li>
          <li>This is the third item.</li>
        </ol>
      </td>
    </tr>
  </table>

.. |smiley| image:: ../images/smiley.png
