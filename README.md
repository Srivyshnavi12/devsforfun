<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dev's for fun</title>
    <style>
        body {
            background-color: rgb(28, 27, 27);
            color: white;
            width: 50vw;
            margin: 0 auto;
            justify-content: center;
        }

        #heart {
            color: red;
        }

        h1 {
            display: inline;
        }

        xmp,
        h4 {
            display: inline;
        }

        img {
            width: 400px;
        }

        code {
            color: red;
        }

        .code {
            background-color: rgb(53, 46, 46);
            width: 400px;
            padding: 7px;
        }

        .green {
            color: rgb(8, 131, 8);
        }
    </style>
</head>

<body>
    <h1>dev's for fun(<h1 id="heart">❤<h1>): day 4</h1>
            <p>welcome to day 4!<br>
                <br>
                in today’s, we’ll be going through a little bit of html & css after which you’ll be challenged to create a few things on <a href="https://codepen.io">https://codepen.io</a><br>
                <br>
                you don’t have to watch day 3 session. this notes will get you up better than the video does. time is precious. i respect yours, therefore this advice.<br>
                <br>
                you don’t have to submit the update for this in a single day, please take your time. the exercise will help you remember and get used to things that matter in HTML (you’ll still have a lot to learn tho!).<br>
                <br>
                and, this note is purposefully made long and time-consuming to make sure you explore and learn about various things, on your own (learning on your own is more important than any other skill, to become a programmer or a developer)<br>
                <br>
                if you want to remember these things, i strongly suggest you come back to this note a second time,around 3 days after you finish it for the first time.<br>
                <br>
                before you continue, please sign up on codepen and then proceed with the practice. otherwise, you won’t be able to save your work.<br>
                <br>
                quote of the day:<br>

                *“<i>tell me and i forget, teach me and i remember, invlove me and i learn</i>” - benjamin franklin<br>
                <br>
                let’s talk some tech now.
            </p>
            <h2>HTML</h2>
            <p>here's what you'll be learning</p>
            <ul>
                <li>a little about HTML</li>
                <li>headings tags</li>
                <li>paragraph tag and <xmp><br></xmp> tag</li>
                <li>links and images</li>
                <li>lists</li>
            </ul>
            <h3>A little about HTML</h3>
            <h4>HTML:</h4>
            <p>Hyper Text Markup Language</p>
            <h4>Hyper Text:</h4>
            <p>text that links to other documents</p>
            <h4>Markup Language: </h4>
            <p>a language to mark things!</p>
            <h3>Heading Tags</h3>
            <p>We have 6 types/sizes of headings in HTML. They are:</p>
            <img src="https://devsforfun.notion.site/image/https%3A%2F%2Fprod-files-secure.s3.us-west-2.amazonaws.com%2Fbe05161a-71c5-47a4-8aad-b71764c4776f%2F60280c64-1186-4fdb-8a4a-ccac97405cd8%2FUntitled.png?table=block&id=27d78108-c2de-472e-ab24-120965b5fd7d&spaceId=be05161a-71c5-47a4-8aad-b71764c4776f&width=1530&userId=&cache=v2"
                alt="...">
            <p>As you may have already noticed, each of them is of different size, indicating different levels of heading, just like in a book (like the Book’s name, chapter’s name, topic name, and so on).</p>
            <p>Here,<xmp><h1></h1></xmp>is called a tag. <xmp><h1></xmp> is called the opening tag and <xmp></h1></xmp> is called the closing tag.</p>
            <p>And, all of <xmp><h1>Hello World!</h1></xmp> is called an element. Why do you have to learn what it’s called</p>
        <p>They help you communicate your ideas/doubts with others, and for googling. knowing the terms will help you clearly describe the problem you have and thus, easily find a solution for it.</p>
        <h3>Paragraph tag & other text formatting text </h3>
        <p>A paragraph tag is usually used to create a paragraph.
            <br>
            It looks like this: <xmp><p></p></xmp>
            <br>
            Here’s how it would look like if you used it:
        </p>
        <img src="https://devsforfun.notion.site/image/https%3A%2F%2Fprod-files-secure.s3.us-west-2.amazonaws.com%2Fbe05161a-71c5-47a4-8aad-b71764c4776f%2F47e24238-403a-4a5f-a0ac-04bfe28ea317%2FUntitled.png?table=block&id=0e7eb617-d063-40f4-9e54-8d1814570008&spaceId=be05161a-71c5-47a4-8aad-b71764c4776f&width=1530&userId=&cache=v2">
        <p>Now, what if you wanted each of the topic names on a different line? <xmp><br></xmp> tag to the rescue!
            <br>
            <xmp><br></xmp> is a special tag that breaks text to a new line. (it doesn’t have a closing tag!)
            <br>
            ⚠️**challenge:** add <xmp><br></xmp> tags to make the above look like this:
        </p>
        <img
            src="https://devsforfun.notion.site/image/https%3A%2F%2Fprod-files-secure.s3.us-west-2.amazonaws.com%2Fbe05161a-71c5-47a4-8aad-b71764c4776f%2F0735d88b-8d69-4536-9a79-16b38d683682%2FUntitled.png?table=block&id=cad2cd7d-55a1-4abd-834f-c70bfb34e543&spaceId=be05161a-71c5-47a4-8aad-b71764c4776f&width=910&userId=&cache=v2">
        <h3>Links & Images</h3>
        <p>We can use text to add links to other websites, just like you see in our emails, using the anchor tag.
            <br>
            Here’s an example:
        </p>
        <img src="https://devsforfun.notion.site/image/https%3A%2F%2Fprod-files-secure.s3.us-west-2.amazonaws.com%2Fbe05161a-71c5-47a4-8aad-b71764c4776f%2F9b416426-1935-4cb6-800c-e461b8b6a347%2FUntitled.png?table=block&id=e9382acb-add5-4246-b4b8-1ad7bede0bd0&spaceId=be05161a-71c5-47a4-8aad-b71764c4776f&width=1530&userId=&cache=v2">
        <p>In the code above, you see some extra text inside the opening <xmp><a></xmp> tag: </p>
        <a href="https://devsforfun.netlify.app">href="https://devsforfun.netlify.app"</a>
        <p>Here, <code>href</code> is called the attribute of the <xmp><a></xmp> tag, and the website URL is called it’s value.
            <br>
            So, if you click on the blue text, you’ll be taken to that page.
            <br><br>
            ⚠️ **challege:** right now, if you click on the link, the website opens in the same window. find out how to make the link open in a new tab.
            <br><br>
            Similarly, we have the <xmp><img></xmp>tag that doesn’t have a closing tag. it’s used to put images in a website. like so:
        </p>
        <img
            src="https://devsforfun.notion.site/image/https%3A%2F%2Fprod-files-secure.s3.us-west-2.amazonaws.com%2Fbe05161a-71c5-47a4-8aad-b71764c4776f%2F69dbcc1e-454a-49a3-a345-1575691a30c4%2FUntitled.png?table=block&id=c0aed4df-0305-4039-8175-9557fa5d2f7d&spaceId=be05161a-71c5-47a4-8aad-b71764c4776f&width=1530&userId=&cache=v2">
        <p>Ss you can see, just like how the <xmp><a></xmp> tag had an attribute called <code>href</code> that we used to create a hyperlink (or a link to another website), the <xmp><img></xmp> tag has the <code>src</code> attribute where we give the image’s URL as value to make the image appear on our website.
            <br>
            How do you get image URLs? just google for your favorite image, right-click on it, and click on<code>copy image address</code>
            <br>
            Sometimes, images might be too large for the screen. find out how would you adjust it’s <code>width</code> and <code>height</code>? (hint: there can be more than one attribute to a tag. or you can just google it.)
            <br>
            ⚠️ Why do some people write <xmp><br /></xmp> instead of <xmp><br></xmp>? (google it)
        </p>
        <h3>Lists</h3>
        <p>In the paragraph’s section, we put all the topic names on a different line. wouldn’t it look nicer if they were a bulleted list? this is something i’ll leave for you to explore.
            <br>
            The output should come out something like this:
        </p>
        <img
            src="https://devsforfun.notion.site/image/https%3A%2F%2Fprod-files-secure.s3.us-west-2.amazonaws.com%2Fbe05161a-71c5-47a4-8aad-b71764c4776f%2Fb17018b1-1619-429a-9630-577e578f42de%2FUntitled.png?table=block&id=a1ebb827-b280-4849-91bb-be7e92bd8828&spaceId=be05161a-71c5-47a4-8aad-b71764c4776f&width=1040&userId=&cache=v2">
        <p>There’s another type of list too. that’s called a numbered list. find out and use it here as well.</p>
        <img
            src="https://devsforfun.notion.site/image/https%3A%2F%2Fprod-files-secure.s3.us-west-2.amazonaws.com%2Fbe05161a-71c5-47a4-8aad-b71764c4776f%2F1e3ecae1-c3ef-404a-8c7a-5117811557c6%2FUntitled.png?table=block&id=969e85db-6fa7-4045-804d-df3381317649&spaceId=be05161a-71c5-47a4-8aad-b71764c4776f&width=1010&userId=&cache=v2">
        <h2>CSS</h2>
        <h4>CSS:</h4>
        <p>Cascading Style Sheets
            <br>
            here’s a peek at how CSS code looks like:
        </p>
        <img
            src="https://devsforfun.notion.site/image/https%3A%2F%2Fprod-files-secure.s3.us-west-2.amazonaws.com%2Fbe05161a-71c5-47a4-8aad-b71764c4776f%2F8a2c7cb6-2624-493a-9a0b-becc849ebdfe%2FUntitled.png?table=block&id=000885fa-fb80-4a3b-98ed-1e4c51c6e03a&spaceId=be05161a-71c5-47a4-8aad-b71764c4776f&width=1530&userId=&cache=v2">
        <p><b>selector:</b> it is the element that you want to make styling changes to.
            <br>
            <b> property:</b> it tells about what you want to change in an element
            <br>
            <b>value:</b> well, you guessed it. it defines the change made to the element.
        </p>
        <h3>Let’s format some text</h3>
        <p>Usually, there are several things you can do text. you can change it’s color, size, font, and more.
            <br>
            Let’s do some of this with CSS. but before that, consider the following HTML without CSS:
        </p>
        <img
            src="https://devsforfun.notion.site/image/https%3A%2F%2Fprod-files-secure.s3.us-west-2.amazonaws.com%2Fbe05161a-71c5-47a4-8aad-b71764c4776f%2Fc4f19578-2546-44d2-bc62-a624d2fa2700%2FUntitled.png?table=block&id=15d5b115-f2d4-4008-9b98-2bcf35c196ba&spaceId=be05161a-71c5-47a4-8aad-b71764c4776f&width=810&userId=&cache=v2">
        <p>Here’s the output after applying some CSS:</p>
        <img
            src="https://devsforfun.notion.site/image/https%3A%2F%2Fprod-files-secure.s3.us-west-2.amazonaws.com%2Fbe05161a-71c5-47a4-8aad-b71764c4776f%2F83bf47a2-70ac-4a38-b88d-a30854ccb647%2FUntitled.png?table=block&id=9f960423-ebe9-4917-b611-553753bbd114&spaceId=be05161a-71c5-47a4-8aad-b71764c4776f&width=1530&userId=&cache=v2">
        <p>Sometimes, images might be too big for the screen. in that case, you can apply the width & height for the image using css!
            <br>
            Here’s how you can do it:
        </p>
        <img
            src="https://devsforfun.notion.site/image/https%3A%2F%2Fprod-files-secure.s3.us-west-2.amazonaws.com%2Fbe05161a-71c5-47a4-8aad-b71764c4776f%2Ff501acc6-3edf-4303-9446-5fac6a146adc%2FUntitled.png?table=block&id=633e9e45-0538-49cb-8019-a696fdc19e36&spaceId=be05161a-71c5-47a4-8aad-b71764c4776f&width=900&userId=&cache=v2">
        <p>Note the<xmp><img></xmp> selector here, the property <code>width</code> is set to a value <code>150px</code>
            <br>
            - what is <code>150px</code>?
            <br>
            Usually, <code>px</code> stands for pixels. It is a unit to measure things on a screen.
            <br>
            Pixels are dots on the screen. The number of dots in one direction tells you how long that screen is, in pixels. An average computer is <code>1920px</code> long horizontally, and <code>1080px</code> long vertically.
            <br>
            Here, <code>width</code> indicates the horizontal length of the image on the screen.
            <br>
            (And, <code>height</code> indicates the vertical length on a screen)
            <br>
            This applies to all tags, not just images.
        </p>
        <h3>3 places you write CSS in</h3>
        <ol>
            <li><b>External CSS:</b> writing CSS outside the HTML file (usually in a .css file) </li>
            <li><b>Embedded CSS:</b> writing CSS inside the <xmp>
                    <style></style>
                </xmp> tag, in the HTML file.</li>
            <li><b>Inline CSS:</b> writing CSS in the <code>style</code> attribute, in the opening tag of a particular.
            </li>
        </ol>
        <p>⚠️ <b>challenge:</b> Find out what happens if you write different styles in all 3 places, for the same
            element.</p>
        <br>
        <h3>More CSS selectors</h3>
        <p>The main purpose of having CSS selectors is to be able to select the elements we want, and style them the way we want them to be.
            <br>
            What if you wanted to select a particular paragraph and make its text green, but you have more than one paragraph tag? This is where we use something called an <code>id</code>
            <br>
            Consider the following HTML code:
        </p>
        <div class="code">
            <h5 class="green">HTML</h5>
            <p><xmp>  <p>first paragraph</p></xmp></p>
            <p><xmp>  <p>second paragraph</p></xmp></p>
            <p><xmp>  <p>third paragraph</p></xmp></p>
        </div>
        <p>Usually, to make a paragraph green, we will use the <code>p</code> selector and set the <code>color</code> to green. But, that will make all the paragraphs green. In order to be able to select only a single paragraph tag, we give that <xmp><p></xmp> tag, an <code>id</code> as an attribute and give a name to it as a value like below:</p>
        <div class="code">
            <h5 class="green">HTML</h5>
            <p><xmp>  <p>first paragraph</p></xmp></p>
            <p><xmp>  <p id="trun-green">green paragraph</p></xmp></p>
            <p><xmp>  <p>another paragraph</p></xmp></p>
        </div>
        <p>You can give it any name. Now, you can use this <code>id</code> to select that particular paragraph and style it:</p>
        <div class="code">
            <h5 class="green">CSS</h5>
            <p>
                <xmp> #turn-green {
                    color: green;
                    }
                </xmp>
            </p>
        </div>
        <img
            src="https://devsforfun.notion.site/image/https%3A%2F%2Fprod-files-secure.s3.us-west-2.amazonaws.com%2Fbe05161a-71c5-47a4-8aad-b71764c4776f%2F801def5c-7aea-4ea7-9370-ade32fff5bc0%2FUntitled.png?table=block&id=083fa154-2437-4e87-913c-2130391a6b9d&spaceId=be05161a-71c5-47a4-8aad-b71764c4776f&width=1530&userId=&cache=v2">
        <p>Note that the name of the <code>id</code> is preceded by a <code>#</code> sign like this:
            <code>#turn-green</code> . That is how you tell CSS that it is an <code>id</code>.
            <br>
            You can only use an `id` with only one element. You can try to use it with other elements and the styling may still apply to all of them. But, that is not recommended because this will cause strange behavior of the code when writing JavaScript (we’ll talk about this again with JavaScript.)
            <br>
            What if you wanted to color the first and last paragraphs in the above HTML code with the color? You can give a common <code>class</code> to both of them and write your styles with the class.
            <br>
            What is a <code>class</code>? it is just like an <code>id</code> but you can use it with multiple tags. Here’s the HTML code:
        </p>
        <div class="code">
            <h5 class="green">HTML</h5>
            <p><xmp>  <p class="purple-text">first paragraph</p></xmp></p>
            <p><xmp>  <p id="turn-green">green paragraph</p></xmp></p>
            <p><xmp>  <p class="purple-text">another paragraph</p></xmp></p>
        </div>
        <p>and the CSS:</p>
        <div class="code">
            <h5 class="green">CSS</h5>
            <p>
                <xmp> #turn-green {
                    color: purple;
                    }
                </xmp>
            </p>
        </div>
        <p>Note that the name of the class is preceded by a . symbol in the CSS code.</p>
        <img
            src="https://devsforfun.notion.site/image/https%3A%2F%2Fprod-files-secure.s3.us-west-2.amazonaws.com%2Fbe05161a-71c5-47a4-8aad-b71764c4776f%2Fc25335f2-ff56-4275-a614-5d6d95145af1%2FUntitled.png?table=block&id=39d63024-8688-4fa2-81e2-4897e1328977&spaceId=be05161a-71c5-47a4-8aad-b71764c4776f&width=1530&userId=&cache=v2">
        <p>
            And that’s all for today!
            <br>
            ⚠️Oh and, here’s the real challenge for the day (take your time on this, it may take a lot of time, and you’ll be submitting this update in a ):
        </p>
        <ol>
            <li>Create an account on codepen.io if you haven’t.</li>
            <li>Create a new pen.</li>
            <li>Replicate this notes page!</li>
        </ol>
        <p>Here are a few things to make this challenge a bit easier.</p>
        <ul>
            <li>You don’t have to create the top bar with the search button, three dots, etc.</li>
            <li>Start from the biggest heading.</li>
            <li>Use different levels of heading wherever you feel they’re appropriate.</li>
            <li>Find out how you can turn a small part of text inside a paragraph into bold text</li>
            <li>For the text in red, you can enclose the text with the <xmp><code></code> </xmp>tag.</li>
            <li>For images, you can just right-click on an image > copy image address > paste it into your project</li>
            <li>Do not worry about formatting the code snippets too much.</li>
            <li>All the links should work, and open in a new tab.</li>
            <li>It’s okay to not center the images.</li>
            <li>The heart symbol is just an emoji.</li>
            <li>If you’ve followed the notes completely, trying out everything that was mentioned above, you should have all the answers to the questions that might arise while building this website.</li>
        </ul>
        <p>If you have any doubts, please feel free to mail us at devsforfun.team@gmail.com
            <br>
            Take your time on this one and I’m sure you won’t forget these things that easy.
            <br>
            wish you all the best!
            <br>
            — charan
            <br>
            follow <i>devsForFun(❤️)</i> here:
            <br>
            <a href="https://twitter.com/devsForFun">https://twitter.com/devsForFun</a>
            <br>
            <a href="https://www.linkedin.com/company/devsforfun">https://www.linkedin.com/company/devsforfun</a>
        </p>
</body>

</html>
