---
time of lesson: 2024-01-04T16:50:00
tutors:
  - Thomas Leigh
  - Thembani Ketse
client: Bilal Noorgat
---

## Assignment
Dear Bilal,

Your task is to populate the files for each of the topics listed below with your understanding of them. Currently, the topics are placeholders and contain no information. Challenge yourself to be creative and in-depth in your explanations. You may use resources like ChatGPT, but copy-pasting its output won't benefit you in any way, so let's avoid that.
## Topics:
- [[The print() function]]
- [[Comments]]
- [[Arithmetic operators]]
- [[PEMDAS - order of operations]]
- [[The basic data types in Python]]

> press `ctrl + G` to open the local graph view.

> To record your insights directly into the file, simply open your command palette (press `ctrl + p`) and enter "Audio Recorder.

Best of luck, and I look forward to discussing these with you soon!

[[Session 1.canvas|Click here to view mind map for Session 1.]]

## Summary of Session 1
Bilal, Thomas and Thembani have their first Python programming lesson in Replit. They cover the print() function, comments (#), arithmetic operators, order of operations (PEMDAS), the modulo operator (%), and end on the different data types in Python: strings, integers and booleans.


> *Please note the dropdown toggle beside `Transcript` used for expanding and collapsing the transcript.*

## Transcript

![[session 1.mp4]]
###### THOMAS LEIGH

It. Awesome. Copy that. And then I have a link. Okay, so I have a URL that I'll need you to open from your phone.
###### BILAL NOORGAT

Sure.
###### THOMAS LEIGH

Obviously we haven't set up Discord is how we would primarily do it. So I'm wondering.
###### BILAL NOORGAT

I said I had discord and then I deleted the app. I never really got the hang of Discord. I always struggled with it, but that's because I was never part of any meaningful community.
###### THOMAS LEIGH

Yeah, Discord has never opened really for me either. I've struggled with it for years, but I worked on slack for a long time and just this media, ideal for slack. But it's a great way that we can collaborate and share files. So you must let me know.
###### BILAL NOORGAT

I got the replicate link. Open the one you sent me. Yes, I see, you sent me another chat OpenAI link. Let me open that one. This is your custom GPT fluently tech, right?
###### THOMAS LEIGH

Yes, it is.
###### BILAL NOORGAT

Okay, cool.
###### THOMAS LEIGH

So what is our custom GPT? I'm going to explain how we're going to run through these lessons. So I'm going to introduce certain code snippets to you. And step one is I'm going to actually have you write them out. Just writing it out. And as you write it, we're going to understand layer by layer new concepts and we're going to speak about it. But as that happens, I want you to have your phone, your iPhone in your hand with your fluently tech GPT open.
###### BILAL NOORGAT

Okay?
###### THOMAS LEIGH

I want you to actually, and we will do this together. So you will see. But what's unique about the fluently tech GPT is it's dead. It doesn't respond to you at all, but it's a way that we can leverage the dictate feature. If you've noticed how excellent the dictation feature is on chat, you can press a little wavelength next to your headphone button and you can talk very casually and it will perfectly transcribe everything you say. And I haven't found anything as effective as that. So yes, really, what the majority of our lesson is going to be is we're going to first of all write out some basic code and then we are going to record our insights and we're going to draw distinctions and we're going to ask questions and all of those, we're going to log into this fluently recording device that is just going to respond with nothing. And then I see, I want us to think with the mentality of how can I extract as many questions as possible from this code snippet that I don't understand. And then once I have no more questions and once I feel like, okay, that's pretty fair, then we will move on to the next code snippet. We're not even looking for answers right now. We're just gathering. We're going to gather questions and we're going to gather insights. I believe it's a fantastic way to learn. I also think that, you know what, questions are almost like a search engine to life. If you ask, you are preemptively looking for an answer. It's such an excellent way of just pouring information down your brain. So I decided to get into it.
###### BILAL NOORGAT

I have fluently tech GPT open on my phone. I don't know whether the discord is taking forever to download on my phone.
###### THOMAS LEIGH

Yeah, it's okay. You know what? We're not going to deal with discord today.
###### BILAL NOORGAT

Okay, good.
###### THOMAS LEIGH

So it's enough if we've just got our replete open, we've got our multiplayer code editor and we have our fluently available here. So we are going to start in the material folder. You can see it in your sidebar. Open up your material folder and go to one. And go to 1.1. I want you to click on that for me.
###### BILAL NOORGAT

Okay.
###### THOMAS LEIGH

And then you just tell me you're going to see this illustration.
###### BILAL NOORGAT

Yes. Hello, world. Hello again.
###### THOMAS LEIGH

I want you to click and drag on the tab. I might share my screen if I'm not being clear, and I want you to place it at the bottom right of your screen. So I'm going to share my screen because I want to show you. Just show you what?
###### BILAL NOORGAT

When you say click and. Okay, sure.
###### THOMAS LEIGH

Okay. I hope you can see from this side. So if you opened, it would be somewhere in the left, drag at the bottom right. So your screen is going to look like this. We're going to go to our main py. So this is exactly what your screen should look like. You should see your print welcome from your main py. And then you should see your console and your shell at the top right. And then you should have your image the bottom right.
###### BILAL NOORGAT

Just quick question.
###### THOMAS LEIGH

Yes.
###### BILAL NOORGAT

Since you are recording the lessons, will I have access to the recording in case I want to revise or review or see something?
###### THOMAS LEIGH

Yes. You will send that to you.
###### BILAL NOORGAT

Great.
###### THOMAS LEIGH

Yes.
###### BILAL NOORGAT

Okay, cool.
###### THOMAS LEIGH

Okay. Are you set up with this?
###### BILAL NOORGAT

Yes.
###### THOMAS LEIGH

Okay, awesome. What I want you to do now is I want you to go to line three of main py and I want you to write it out. I want you to actually write because again, when you start with Python, the first thing is just actually trying to get that muscle memory of writing it out. I want you to write out this text segment and allow for the silence as we just watch you time.
###### BILAL NOORGAT

It kind of knows already. How come it knows it?
###### THOMAS LEIGH

Hold on, hold on. You know what? This is good that we're starting out. No, not wonderful at all. Wonderful that we're seeing. It's wonderful that we're seeing it. I need you to press. We're going to fix this command. You're on Windows control k. Control a. Control K, the letter K for.
###### BILAL NOORGAT

Okay, got it.
###### THOMAS LEIGH

And then type in settings and you should see it's going to pop up. User settings.
###### BILAL NOORGAT

Yes.
###### THOMAS LEIGH

And then we want to scroll down in user settings and we want to turn off AI code completion.
###### BILAL NOORGAT

Wow.
###### THOMAS LEIGH

Yeah. I'm deciding not to go on a rant about how amazing AI code completion is. And you know what? We are really living in the golden era of programming. Despite many that programming won't exist in five years. We are moving to a space of profound opportunity and something at this point, without taking us off the point, why is it important for us to switch that off? And why is it important for us to understand how to program, to understand Python or whatever other language, but specifically Python? Because these tools can do the work for us. I can just tell it, hey, do this for me. And then it can just spew it out and I can sort of make it work. And the magic really comes into play where I understand what I'm looking at. So when AI generates code for me, what becomes a weapon in my hands is when I can look at the code and I can understand what I'm looking at, I can communicate with what I'm looking at, rather than just trusting that the AI is giving me the right code and you can critique it and you can critique it and then you can actually correct the AI where it's wrong. You can say, no, you need to fix this. You have an oversight for the year and that's really where we're going.
###### BILAL NOORGAT

My brother told me that it's painful when you have to debug code because sometimes there are errors and you have to figure out, and that's where he spends a lot of time.
###### THOMAS LEIGH

Yeah. When did your brother learn to code?
###### BILAL NOORGAT

A couple of months ago.
###### THOMAS LEIGH

Okay. Yeah, since Chat GPT.
###### BILAL NOORGAT

Yeah, since Chat GPT.
###### THOMAS LEIGH

You know what? Yes. Errors can be a pain, too. I don't think errors are a pain to debug at all, especially is out. And you can simply say, why is this giving me an error? Explain it to me, like, I have no experience in programming, can do a very good job getting stuff. So, yes, you know what? The learning curve and the barrier of entry that was previously in place with programming has just flung open. And that's a good thing. I've deleted three of your lines. I want you to type them again.
###### BILAL NOORGAT

Okay.
###### THOMAS LEIGH

Get rid of that autocompletion. So you want to press shift Tab just to backspace out of that shift tab. Tab will bring you four spaces in, and then shift tab will bring you back. So press tab.
###### BILAL NOORGAT

That's tab, right?
###### THOMAS LEIGH

That's tab, yes. And then you press shift the other way. That's level two. We don't need to know level two yet. Indentation is required.
###### BILAL NOORGAT

Indentation project.
###### THOMAS LEIGH

Yeah.
###### BILAL NOORGAT

Okay, done. Should I press run?
###### THOMAS LEIGH

That's a good question. You could, but before you do that, why is there squiggly line on line seven? And you know what I'm going to do? This is a perfect transition. I've just copied this code and I am pasting it in my GPT. This site. Yeah.
###### BILAL NOORGAT

I figured out what's the problem here.
###### THOMAS LEIGH

Maybe, and I'm going to say, so I'm demonstrating an example of how we were to do, hey, here's this code snippet. I'm learning Python and I see this red squiggly line underneath the line seven, and I really understand it, but I've just noticed that it's my first question and really I'm deciding to document every question that I have. So, yeah, my first question is just like, oh, hey, what's going on here? And simple as that, I'm going to move on.
###### BILAL NOORGAT

Wow, interesting. So basically you're documenting. So you copied the code into that custom GPT and then you ask a question. Obviously it's easy through the voice notes. So you just ask a question and you want to document your question. Basically, yes.
###### THOMAS LEIGH

Look, I'm going to open up, you're going to go into your chat, I want you to open this in a new tab.
###### BILAL NOORGAT

Okay.
###### THOMAS LEIGH

So this is our first example of how we're going to relate to these AI tools.
###### BILAL NOORGAT

Okay? So I'm demonstrating example of how we were to do this. I'm going to say, hey, here's a code snippet. I'm learning Python. Okay?
###### THOMAS LEIGH

So all that I've done, my site, and what you will do, your site is you'll have fluently tech GPT open on this site and you will simply start a voice recording. And you are just mentioning the snippet of code and you're just like, hey, I'm learning about Python. And I see I'm just documenting my questions here. Fluently tech, you can see response to nothing icon pop up. So we are going to save every insight, not just question, but every insight. We're going to draw distinctions and this is how we're going to learn. And then you're going to see how supercharged we're going to learn because we have listen, if we had Chat GPT give us information overload for every single question that we asked. That's not what we want right now. We're going to simply ask questions for the sake of storing them. So this is just my example. Close the tab, we can run back to replit.
###### BILAL NOORGAT

Okay.
###### THOMAS LEIGH

This is a perfect time now for screen share. No screen sharing. Okay, so what about lines seven? Line seven is not identical to code example. Okay, perfect. I want you to open up your fluently tech GPT. I want you to press that wave button, and I want to hear you make sense of lines three to nine. I want you to make sense of it. So I want you to just speak about the difference in which quotation marks you're using. I want you to questions or think about how could it break? And we're going to run through the code, we're going to see what happens. But I want you to log your first question, or, hey, from this code snippet, I can see that what they're trying to teach me is the difference. That's what I want from you. So you can go ahead when you're ready.
###### BILAL NOORGAT

I'm learning Python, and the instructors have given me a code snippet to type into replicate. And of the six or seven things that I typed in, I noticed that some of them have inverted commas wrapped around the text, double inverted commas, whereas one or two of them have a single apostrophe wrapped around the text. And I'm trying to understand what is the difference between having inverted commas wrapped around a text versus an apostrophe.
###### THOMAS LEIGH

Awesome. Great question. Now, my question for you. Did you press the. Which of these buttons did you press? Do you press the headphone or did you press the wavelength?
###### BILAL NOORGAT

So I pressed the headphone because.
###### THOMAS LEIGH

I.
###### BILAL NOORGAT

Pressed the headphone, but now I see that there's a wavelength I should have pressed, right.
###### THOMAS LEIGH

You'll notice it still didn't respond. So you can. And if you press the cross out button at the bottom left and you exit, you will just see the text there.
###### BILAL NOORGAT

I can see the text. Yeah, I can see the text.
###### THOMAS LEIGH

Good. I'm going to log on from my side for you. You can see my looks like this.
###### BILAL NOORGAT

Yes.
###### THOMAS LEIGH

Hey, so it's day 1 hour one of learning Python, and I have a bunch of lines of code that says print and then it opens up brackets and then we have text in there and it's surrounded by quotation marks and will sometimes be surrounded by apostrophes. But listen, man, I have no experience in this. I just don't know what concepts I'm looking at. I'm also maybe ready to move on. I think I understand this, but what is this print thing? I just could do with a better explanation about this print thing. What is it? What is print? What else in Python can I put in there other than print? What does print do? I think I know what print does, but what else can I put in the brackets of print? So I think that's really all of the questions that I can extract from this for now, probably good. And then you can see it's converting a text.
###### BILAL NOORGAT

And how long can that voice not be? As long as you talk.
###### THOMAS LEIGH

10 minutes. I've had a ten minute, but I think it's better to just isolate each question because it takes a long and will sometimes crash when you have a really long voice note. So I kind of keep.
###### BILAL NOORGAT

Are you using an iPhone?
###### THOMAS LEIGH

Yes, I am.
###### BILAL NOORGAT

Is there a shortcut like one button you can press and you're automatically recording your voice note? Or do you have to open the app and then press the wavelength button?
###### THOMAS LEIGH

Kind of. So that's an iPhone question. I'm going to swap my focus to work if you look over here. So here's my home screen. I slide down to my lock screen. Since the iOS update of either iOS 16, you can add widgets on your home screen and this widget over here, if you press it, it's going to take you straight to Chat GPT.
###### BILAL NOORGAT

I see.
###### THOMAS LEIGH

And have a widget that takes you straight to the audio Chat GPT so it immediately starts a conversation.
###### BILAL NOORGAT

Wow, nice. Okay, cool.
###### THOMAS LEIGH

Yes. Okay, I want you to show me now before we move on from this code, I need you to understand how it could break. I want you to break this code. Hold on. Let's first run the code. You can run the code run at the top, the green button, or you can press control enter.
###### BILAL NOORGAT

Okay. Hello world. Hello again. I like typing Spaniard much. Not okay. You said control enter is also another way to run code.
###### THOMAS LEIGH

Yes. And really the better way. You want to run code, you want to press Ctrl enter, but it's natural, it's faster okay, here's another question. I'm going to ask it for you because I want to get the ball rolling and I want you to see how I'm engaging in this. So I've printed the outputs of these print functions and it seems that it prints whatever I put inside of it, which in my experience is just text right now. It prints it to what's called the console or the terminal. I don't have any experience in the terminal, but I understand the terminal is related to programming. So anyways, I've printed hello world. I've printed hello again. I've printed text examples that include quotation marks, and I've printed text examples that include apostrophes. And there's an insight there. So, yes, I think what I'm going to do next is I'm going to think about what can't I do? And then once I click with that, I think I'm ready to move on. Mmm, good. So I've written that down. I saved that so you can see from your console you've got. I'd much rather you not, and I said not to touch this, but if you look on line eight and line nine, you should see the difference in how we are surrounding that text.
###### BILAL NOORGAT

Yes.
###### THOMAS LEIGH

I want you to record yourself and explain on line eight and nine and what insight there is to unlock. In looking at these.
###### BILAL NOORGAT

I'm looking at two lines of code, and the first line, it's text based and it's wrapped with inverted commas, and within that there is one word that is wrapped with apostrophe. The next line of code, the line is wrapped, it's text based and it's wrapped with an apostrophe. But within that text there is a word that is wrapped with inverted commas. And I'm trying to understand what is the impact of having words wrapped with inverted commas versus apostrophe, and within the text, having a word wrapped with apostrophe and inverted commas. So can you please explain that to me? Okay, it's converted it to text, and now I'll hit enter. So it's all, save it.
###### THOMAS LEIGH

So what we've learned about thus far, we've learned about the print function. So in python function, it's actually a built in function, which we don't really need to know about right now, but it's a built in function designed by built in function, meaning that it's embedded in a default path in a default part of python. It's basically saying, hey, whenever I run print and I open up my parentheses and I pass in content inside of that, it's going to send it out to the console, and that's what that function does. And then we've learned about. Really, we've learned about printing text in Python. That's what we've spent our 1st 30 minutes on. Okay, we're printing text in Python and we've used the print function and we have worked with text. Worked with. Our text is expressed in Python, so all human text that you write is surrounded by quotation marks. Now I want us to do something.
###### BILAL NOORGAT

Quick question. So I have two screens, obviously, and I can see you typing on when you're typing. I can see it happening on my replica screen. But is the screen recording this zoom screen with our names and your video, or is it.
###### THOMAS LEIGH

No. So our recording is simply recording the two of us. It isn't recording what's happening in our discussion. But I see our meeting is over. You will have access to all of the code snippets that we went through.
###### BILAL NOORGAT

Okay, that's fine. It's all right. I think it's fine for now. But perhaps maybe when we get more advanced or when things get a bit more complex, can we record the screen where we have?
###### THOMAS LEIGH

Good.
###### BILAL NOORGAT

Alternatively, I could also record myself. I think I do have a screen recording.
###### THOMAS LEIGH

I mean, I couldn't record the screen for you. It depends. I could probably, if I were to start screen sharing because you say we have. I'm going to go to replet here. I'm going to share this because you have two screens. That would simply mean if we are talking to each other like this. Yes, this is acceptable for you that you can still.
###### BILAL NOORGAT

Yeah, this is good. This is good.
###### THOMAS LEIGH

From here on we are saving. That's good. Thank you. Belar. So before we move on, you can see that we have learned about how to make comments. I want you to go to the material in the material folder, 1.2 comments and I want you to drag it in the tab next to printing so you can see on my screen what I've done.
###### BILAL NOORGAT

I see. Okay.
###### THOMAS LEIGH

So in that example it says you can print. I could have code like this. And the comment after it is ignored.
###### BILAL NOORGAT

Understand?
###### THOMAS LEIGH

Comments are written with the hashtag symbol. There was a pound. Octothorp. Very weird name. That's also. And if you want, many years ago.
###### BILAL NOORGAT

I took a few classes on c plus plus. Like three classes on c plus plus. I don't know why. And I remembered they use what's it? Backspace, not the straight line, the crooked line. For comments like two crooked lines for comments. Yes. Backslash. Backslash, yes. But yeah, if you're using hash. Hash. Okay. Yes.
###### THOMAS LEIGH

That's comment in c plus, guys.
###### BILAL NOORGAT

I see. Okay, cool. So I got the comment. Now let me put in the comments so you can also. Actually, I think someone told me, a friend of mine told me to take c plus plus. He was a data scientist, and he told me to take c plus plus if I want to understand, learn data science.
###### THOMAS LEIGH

Very interesting. You know what, just while you're typing. For years, I always thought that programming was not for me. I. Philosophy degree. I studied philosophy for three years in politics and psychology and law. And I saw programmers as, I just thought it was not for me. I thought it was like alien and technical. But in recent years, I've seen programming in a whole new way. Because programming, for me, the reality of what programming is, it's a way for you to enhance your creativity. Like literally creativity, your ability to create from what you imagine. It's a technology. It's a toolbox by which you can design and create what's in your mind, which I think fascinating.
###### BILAL NOORGAT

Up until now in my life. So I know, I believe that anything I put my mind to and anything I put a lot of time into, I can do it. And I feel coding is coding. And learning a language is something that requires a lot of commitment. And I didn't have the time up until now because of a full time job, I didn't have the time to commit. So is it true that you need to commit? The time you have to put in the hours to become good at it? Is that true?
###### THOMAS LEIGH

That's true for everything in life. I will say that programming is really hard to learn. There are a lot of people. It took me five years of trying to learn programming before I actually did it. And it's true for a lot of people. I'm a strong proponent in one on one tutoring because I believe that if you were to do it on your own, there's no accountability system, there's no one who's really tracking your progress and understanding exactly where you're at, and there's just no incentive or disentive to stop or continue. And that's just in my experience. But also, since large language models were unleashed into society, I believe you don't need to spend as much time to understand it. Okay. So you can just run the code again with your control. Enter.
###### BILAL NOORGAT

My computer froze. Give me a second. Okay. I said do not touch this. I could have code like this. This will run. Yeah, I see the comments after the hashes are yes.
###### THOMAS LEIGH

If you go up to line seven and eight, you can comment out line seven and eight with control where your question mark is on your query keyboard. You can click control forward slash I see.
###### BILAL NOORGAT

So the control forward slash, I see. Okay. So you don't have to go put in a hash, you can just use control forward slash.
###### THOMAS LEIGH

Yes. Awesome. So we've learned about printing text in Python. We've learned about the print function. That's our first ever function that we've learned about and how text is expressed in Python. And then we've obviously learned about comments and why use comments? Comments are used to describe your code, literally comment on your code, but it's also used to comment out code. We are like, listen, I'm running this code, I want to see the output of it. I'm going to comment out this line of code to see what the difference is. And really all comments are ignored by your Python interpreter, which is really the Python interpreter is just the computer that's doing the work behind the scenes to run this code and send the output to the terminal. Good. I think there's one more thing I want you to do. I want you to go on lines four and five, and I want you to swap around the quotation marks such that line four begins with an apostrophe and line five begins with a quotation mark. Perfect. Then run it. Okay, this is our first error. We have a error. So what is it telling us? It says it's on line four, so our error is informing us that the error is occurring on line four and it's pointing an arrow to exactly where we're getting the error, and it's telling us what type of error it is.
###### BILAL NOORGAT

Syntax error.
###### THOMAS LEIGH

And then it will say unterminated string literal. So I see you've backspaced it. Backspace it and run it again from here. I want to see what it does from here. Okay, invalid syntax. Perhaps you forgot a comma. So now I want you to comment outline four using control forward slash. And I want you to control enter. Okay, so I want you now to take out your GPT and I want you to record what happened. And, I don't know, pinpoint exactly what you don't understand.
###### BILAL NOORGAT

I'm getting some errors when running code. The first error is an unterminated string literal. And basically what happened is that I have text wrapped in an apostrophe, but within the text I have a word that is also wrapped in an apostrophe. And a second line of code is the error is reading as invalid syntax. Perhaps you forgot a comma and this line of code. I have inverted commas, text wrapped in inverted commas, and within that text there's a word that is wrapped in inverted commas. And I'm trying to understand why am I getting these errors? Um, great. It was listening, it was listening to me the whole time. But when I see now it only gave me one line of text when I spoke to the phone.
###### THOMAS LEIGH

That's not nice. I don't know why it's done that. Okay, again, I haven't experienced that on my site. You see the.
###### BILAL NOORGAT

No worries.
###### THOMAS LEIGH

Are you still there?
###### BILAL NOORGAT

Yeah, I'm here.
###### THOMAS LEIGH

Would you mind just if it didn't save, you wouldn't mind?
###### BILAL NOORGAT

Okay, let me go again. I am trying to run some code and I'm getting some errors. So the first error is a syntax error. It says invalid syntax. Sorry. The first error is a syntax error, unterminated string literal. And the line that it's pointing to is a text line and a piece of text that is wrapped with an apostrophe, but within that text is a word that is wrapped with an apostrophe. And the second error is a syntax error. Invalid syntax. Perhaps you forgot a comma and this one is pointing to a line of text that is wrapped with inverted commas, and within that text is a word that is wrapped with inverted commas. And I'm trying to understand why I am getting these errors. Okay, that one's better. I realize why it never recorded. When you press the headphone, it doesn't record very well, but when you press the wave thingy, it records nicely.
###### THOMAS LEIGH

Yes. Awesome. Okay, I want you to add one more wavelength recording with that blue, I want you to share not a question. Out of everything on this page, what have you learned? I want you to specify what you've learned and try and be specific.
###### BILAL NOORGAT

I've learned how to use the print function, which is basically outputting a string of text, and I've learned to use how to use the control backslash, which doesn't run a text. It's just a comment within your code. And I've learned the importance of the detail around having for text, you need to use either an apostrophe or inverted commas. And I've learned how to obviously run the code in my python interpreter by pressing Ctrl enter.
###### THOMAS LEIGH

Nice. Okay, I now I'd like you to. Where are we going? We're going to open up our material folder .2. We are now going into our operators. Obviously, if I'm sharing my screen, you can see on one side.
###### BILAL NOORGAT

Okay.
###### THOMAS LEIGH

I'll also drag this side, drag it next to printing, just so that on the bottom right, we can keep our illustrations and our attachments. So. Yeah. I don't know how much experience you have in this. I think every person in the 21st century knows how arithmetic is done on a phone or on a calculator, so I'll tell you.
###### BILAL NOORGAT

I work in Excel, so using these operators, I'm quite familiar with it.
###### THOMAS LEIGH

And, you know, exponents or your two asterisks.
###### BILAL NOORGAT

No, the only one here that I'm not so familiar with is the exponents.
###### THOMAS LEIGH

Okay. I'm glad that we're on the same page here in Python and in computer science in general. I think people outside of computer science are accustomed to calling these, if you look on my screen and if you look at the mouse on my screen, to calling parentheses, brackets. Yes, brackets is a good one. But really, the terminology, if you want to have good terminology, they're called parentheses in computer science. And then your square brackets are called brackets and your squiggly brackets, which we're going to go over later. Those are your curly braces.
###### BILAL NOORGAT

Yeah, I see.
###### THOMAS LEIGH

I'm going to open up this then.
###### BILAL NOORGAT

Yeah. Bod math and PeMdas.
###### THOMAS LEIGH

So everyone knows bod math. Okay.
###### BILAL NOORGAT

Yes.
###### THOMAS LEIGH

Brackets of division, multiplication, addition, subtraction, I don't know how well, you know, PEMdas.
###### BILAL NOORGAT

Heard of it, but I don't know it. So, yeah, we'll be.
###### THOMAS LEIGH

Mdas is the same thing, but in a sense more with a better terminology, because you can say brackets and you can say of but what is of really but a mathematical term that they try and squeeze into. So it's the same thing. If you were to do a python exam in the next few months, there will be pemdas in it. And pemdas has to do with the order of operations, meaning the order by which your Python program and your computer is going to process calculating numbers. It's going to first start with everything in your parentheses, and it's going to calculate what's in there. I mean, you know, finance and mathematics. And then you've got your exponents after that. Multiplication and division are on the same level, and addition and subtraction are on the same level. And you can see that with our color code here, we've got yellow and we are moving down.
###### BILAL NOORGAT

For bot mass. Like division is ahead of multiplication, but for pemdas, multiplication is ahead of division.
###### THOMAS LEIGH

Yes. Okay, good that we see. Good that we see this. So it's more like a. Give me 1 second to upload an image. I'm going to upload stuff. If you look on my screen, open for us, a little bit blurry, but we've got. So this is a, it's like a pyramid where the highest are your parentheses and then your exponents. But multiplication division are on the same level and addition and subtraction are on the same level. And you can see that here as well. That's the reason why these are interchangeable. Addition and subtraction are also interchangeable here.
###### BILAL NOORGAT

Okay, but if I give you a formula they say equals two times six divided by two.
###### THOMAS LEIGH

So good. This is an excellent place to start. Okay. Yeah, we're going to jump into main py and let's print that. So on line 21, I see you're back in operation. You want to jump to main py. So I'm going to copy this, I'm going to put it in an archive Python file.
###### BILAL NOORGAT

So when we use print, we print text, right?
###### THOMAS LEIGH

Okay, good. Write that down, because thus far, yes, but you can print more than just text. Yeah, but I want us to understand the difference. We're going to write both these down. Two times by six divided by two.
###### BILAL NOORGAT

On my screen I've been using, starting my code with the word print. I want to understand what is. Wait, sorry. On my code interpreter, I've been starting every line of code with the word print. What does this mean? What does print do? What does print mean? Is it only used to run text or can print be used to run a mathematical formula?
###### THOMAS LEIGH

Excellent question. Good. I want you to run this code with your control enter.
###### BILAL NOORGAT

It's not happening fluently. That tech is actually replying to me.
###### THOMAS LEIGH

It's what?
###### BILAL NOORGAT

It's replied to me.
###### THOMAS LEIGH

Okay, that's interesting. It might, in there, it shouldn't reply unless you have a forward slash answer. So we're going to outside. It shouldn't answer you.
###### BILAL NOORGAT

Actually, it starts the answer with forward slash answer, but I didn't do anything to get it.
###### THOMAS LEIGH

I see. Anyways, answer specifically. Yeah. Okay, what does it say?
###### BILAL NOORGAT

It says, in programming, particularly in python, the print function is used to display information to the user. It can output various types of data, not just text strings. You can use print to show the results of mathematical operations, the values of variables and the output of functions. For instance, print two plus three would display five. And print hello world would show the text hello world. So print is a versatile tool. I see.
###### THOMAS LEIGH

Great. Run your code.
###### BILAL NOORGAT

Okay, so this is giving outputting the text, and this is outputting the six divided by two is three times two, but I guess six. Two times six is twelve. And twelve divided by two is six. Anyway.
###### THOMAS LEIGH

Okay, I want us to break down what's happening on line nine.
###### BILAL NOORGAT

Okay, so print. So you have two plus three times five. You have parentheses, and then you have multiplication, and then you have a comma. And then after the comma, you have parentheses again, which I think what will happen here is that this will give you the text which will be two plus three times five equals. And then it will give you only the answer. So maybe I can drop a question in my chat. So I'm looking at some code and it starts with print and there's inverted commas, so I believe that is text. After that there's a comma and then there's a few numbers which are green in color, but there's no inverted commas. So I think that is running a formula.
###### THOMAS LEIGH

Great. So you just shared an insight. I love that. So we're really differentiating between insights and questions. And I'm going to add a question for my site. I'm looking at a print function that contains within its parentheses, it starts with text surrounded by quotation marks. And inside of it it says two plus three times five, but it's just text. And then there's a comma, and then after that there's the actual sequence of numbers. There's two plus three times five. So it seems like we want to print to the terminal, we want to print the text. Two plus three times five is equal to, and we want the value of that. So what I didn't know until now, that's another excellent way to frame things. What I didn't know until now is that until this point, I had not had any experience passing in more than one item into this print function. I can see you can do that. You can see that we're passing in two items within these parentheses. So, yes, I'm starting to understand it a little bit more clearly. I'm starting to understand that the print function doesn't just receive text, but can also receive numbers, and that my computer, when I run this code, is probably going to automatically calculate those values. Yes, here we go. So that's a high quality insight and question that we are documenting. So, great. Have we run this code? We have not yet run this code.
###### BILAL NOORGAT

Okay, let me run it.
###### THOMAS LEIGH

Comment out lines five and six and then run the code. Great. So you have an interesting point. We just go this one. I'm just going to let you carry on. Okay. So yes, we're going to. Now look at here. Let's print this guy. Run the code.
###### BILAL NOORGAT

Okay, so here we have, speaking of this, exponents two to the power three. Okay.
###### THOMAS LEIGH

Cool. What is the output?
###### BILAL NOORGAT

The output is the text exponents two to the power three. And then it equals which is also text. And it gives you the mathematical answer, which is two to the power three of eight. Nice.
###### THOMAS LEIGH

So now what is going to happen? Print this.
###### BILAL NOORGAT

Okay, let me look at that. Two plus three times ten minus five to the power two. Okay, let me lock something. I'm looking at a formula on my code interpreter and I noticed that there is a percentage sign, and I'm trying to understand what is the impact or what does having that percentage sign do to my code? Okay, let me run that. 46. Okay.
###### THOMAS LEIGH

I'm going to share my screen on a separate application and I'm going to share this. Can you see my screen?
###### BILAL NOORGAT

Yep, I can.
###### THOMAS LEIGH

So this is an app called Thonny, and it's a way of visualizing every step that python takes to process and deconstruct what you've written into printing to the console.
###### BILAL NOORGAT

Okay, what is this called? Funny.
###### THOMAS LEIGH

Funny. You can see at the top, right? T-H-O-N-N-Y-I can't see because it's blocked out.
###### BILAL NOORGAT

By the meeting is being recorded. Okay, cool.
###### THOMAS LEIGH

Okay, hold on. I actually might need to. There we go. Okay, so I'm going to walk through step by step, what questions? I want you to do it. You know what we're going to do? I want you to start a voice recording on Chat GPT. And then I want you for every step. When I click next, you're going to watch. There are going to be about ten steps. And step I want you to explain what is happening. Let me just see if I can make the size a bit bigger for us.
###### BILAL NOORGAT

It's good enough for me.
###### THOMAS LEIGH

Yeah, I'm going to make the size 30. Okay, have you started your recording?
###### BILAL NOORGAT

Okay, so you want me to.
###### THOMAS LEIGH

Basically, I'm going to start, then you're going to take continue from me, but record, it's going to save even me talking. That's fine.
###### BILAL NOORGAT

Yes, sure. Go for it.
###### THOMAS LEIGH

Okay, step one, Python is examining this line. It sees here is a print function. Its question right now is what's inside of this print function. You can see how it's highlighted everything. So Python, already in these two steps, it's been very fast, has understood that, oh, I'm dealing with a print function. So we want to print something. What do we want to print then it looks and then I want you to continue from now because it's going to select portions of it and I want you to reason why it's moving there.
###### BILAL NOORGAT

Did you press next?
###### THOMAS LEIGH

Yes, I have. So here we are. You can continue from here.
###### BILAL NOORGAT

But I can't see anything different. I can still see the full. You mean how is it selecting?
###### THOMAS LEIGH

Are you able to see the highlights, the yellow highlights with the blue?
###### BILAL NOORGAT

No, I can just see. I can't see any highlights.
###### THOMAS LEIGH

How unfortunate. I'm sorry. I see. Sorry about that. I don't understand why I think you.
###### BILAL NOORGAT

Can highlight it with the mouse and then I can follow along like that.
###### THOMAS LEIGH

That's true. You can look on is okay? Yes. Let's look from here. You don't need to record right now. Excuse me for having you record that long.
###### BILAL NOORGAT

No worries.
###### THOMAS LEIGH

So Python is going to start on line one. The moment you click run at the speed of light, it's going to completely ignore all of the comments. It's going to move to the first because comments are invisible to Python. It's going to move to line 13. It's then going to see, there's a print function here. It's going to have selected everything like this. Then it's going to ask, okay, well, what do you want to print? And it's going to highlight this and then it's going to understand that there are several expressions here. So plus and minus, addition and subtraction, separate terms and so how many terms do we have? We have one term, we have two terms, and we have three terms. See that?
###### BILAL NOORGAT

I see.
###### THOMAS LEIGH

And then it's going to start by going inside of our parentheses. So here's where PM Das comes in. And it will first calculate two plus three, which is five. Then it's going to times that by ten. It will calculate that value. Yes. And then we are not minusing it by five. We are minus by this expression.
###### BILAL NOORGAT

I see.
###### THOMAS LEIGH

So that's five to the power of two divided by five. And then again, now the question is, okay, well, is it going to start with two divided by five or is it going to start with the exponent? And if we know hem Das or bodge mass, start with the exponent, which is 25. And then we are dividing it by five, which goes back to five. So we are looking at 50 minus five plus seven percentage sign two. What's going on there?
###### BILAL NOORGAT

Yeah, I had a question. I documented the question about that percentage sign.
###### THOMAS LEIGH

Great. Okay, good. I'm going to copy this. I'm going to log it from my site. Good. I'm going to paste this code snippet, I'm going to say, hey, so I'm learning about Python, and at the moment, I'm learning about numbers in Python, and how numbers are calculated in Python. And I've been reminded about bod mass and what's called pemdas, which is like exactly the same, but with better naming conventions, I guess. And here's supposed to be an example of it. Okay, so I guess I understand it. I can see now, if I look at it for long enough, I can see that everything between my print function, it's going to first separate the expressions by the addition or the subtraction, and then it's going to follow the order of operations is what it's called, where we'll first calculate anything within brackets, if they are brackets, and if there are exponents, I'm going to calculate that first until all I have left is addition and subtraction, and then I'm just going to work that out. I get that. I think it will help if I get more experience with it, but I get it. What's confusing for me is this percent sign. What does this percent sign even do? What does it do? I think when I look at percentage, I think of, like, divide, but I know that forward slash is divide. I've worked in excel for a long time, but I don't know what this percentage sign is. And can you just help me understand pemdas in an intuitive, simple way, please? Thank you. Good is another question.
###### BILAL NOORGAT

Nice. Very nice.
###### THOMAS LEIGH

Currently, in our sum, we're at 45 plus that 7% sine two. So, yeah, where were we at? The result of our first expression was 50. The result of our second expression was five. And then there's seven. It's called medullus. It's called medullus, and it stands for, if I were to divide seven by two, what number is left? So in other words, seven medullo or medullus two is going to be two, goes into 72463 times with one remaining. So I'm going to comment this out and I'm going to print seven medullus two. And when we run this code, it's going to give us one.
###### BILAL NOORGAT

Wow. Is this common modulo used in programming?
###### THOMAS LEIGH

Yes, it is. Wow.
###### BILAL NOORGAT

Interesting.
###### THOMAS LEIGH

Yes.
###### BILAL NOORGAT

Okay.
###### THOMAS LEIGH

You know what? When I learned about medullus, it's like learning about the whole new. It's like there's plus, there's minus. You've grown up your whole life knowing operator arithmetic tool arithmetic. And then you just learn about a new one. It's a new arithmetic operator is what it's called. It simply is like, hey, I'm going to divide 75 by four and just give me the remainder. So that's how that works. Okay, so it's called modulus. I don't expect you to understand it. Now, I expect us to save an insight. So I want you from here to create a new recording where you talk to Chat GPT, and I want you to just speak about, hey, so what I think Modulus is, is this, am I right? That's really what I want me, I want you to try and gain track percentage sign modulus operator.
###### BILAL NOORGAT

I'm looking at a line of code, and we have a formula, a print function with a formula. And within that formula, there's parentheses, there's multiplication, addition, subtraction, but there's a term or an expression within the formula that is seven percentage two, seven percentage sine two, which I understand is a modulus arithmetic operator. And I understand that the way that it works is it is the remainder of seven divided by two and whatever is remaining after the. Yeah, it's a bit confusing to explain that. Medulla formula.
###### THOMAS LEIGH

Great. Is that your recording?
###### BILAL NOORGAT

Yeah, it's my recording.
###### THOMAS LEIGH

I hope you included in. It's like, hey, man, it's confusing. I don't understand. You know what? I really belal, going forward, I'm going to test and push your ability to ask questions and be real with AI. Be like, hey, I don't understand this. Hey, this is boring. Hey, this is whatever. Just learn to communicate well with these insights. And you're doing so. Yes, good. I think I want us to move, I'm going to move all this stuff to the archive, and now I'm going to copy some code into our main py file. Print that out.
###### BILAL NOORGAT

Okay, so we have text. We have text and some formula. I see. So do you want me to run this?
###### THOMAS LEIGH

Yes, run it.
###### BILAL NOORGAT

Okay. Wealthy, rich billionaires. Elon Musk 251 Bernard Arnold okay, so I see the issue here. Let me log the issue in. Chatchi PC. I'm trying to print something on my, using my python code interpreter. I have a list of businessmen or entrepreneurs, and I'm trying to calculate their net worth. When we are running the code, it's printing the names correctly. The text is printing correctly, but the formula is not outputting the way that I would like it to output. So, for example, I printed the text Elon Musk and I want to output the formula. I want to output his net worth of 251.3 billion. But my formula is giving me 25,101 how do I correct that?
###### THOMAS LEIGH

Good. I have an exercise for you that I want you to do now to modify the output to look like this.
###### BILAL NOORGAT

You know what? It's giving me all the answers because this thing is somehow just answering all.
###### THOMAS LEIGH

My, hey, that's so unfortunate. You know what? It's lesson one. We're getting a lot of kinks in the armor.
###### BILAL NOORGAT

No, the good thing is that it actually did understand exactly what I said to it. Now, the two 5101 and why it's not 251.3 billion, and it's telling me what I can do to fix it.
###### THOMAS LEIGH

Interesting. Did it give you a code example?
###### BILAL NOORGAT

No, it didn't. Just told me to consider the following points. Check your formulas. Components. Ensure that the numbers and operations in your formula correctly represent the calculation. Verify data types, review mathematical operations, format the output. If you can share the specific line of code you're using to calculate and print the network, I can provide more targeted advice on how to correct the issue. Okay.
###### THOMAS LEIGH

Do you know what technology we're lacking right now? We're lacking the ability for you to copy the code on your computer and paste it in your Chat GPT on your phone. That sucks. I'm going to figure out what tool we can use to fix that. And we could fix it with discord. Because if you had discord open on another.
###### BILAL NOORGAT

I have Evernote, so I have Evernote on my computer. I have it on my phone. So I could just copy paste.
###### THOMAS LEIGH

But okay, you have Evernote. That's an interesting way. Going forward. If you can copy paste, we won't do that.
###### BILAL NOORGAT

Now, I know you don't like Evernote. You're a notion fan, right?
###### THOMAS LEIGH

I am a notion fan. Notion got me into programming. I'm also an obsidian fan. We're going to be working in obsidian as kind of the homework outside of our classes. And you'll see, I'm going to send you a video about it. But yes, really, what I'm asking from you is I want you to add a new item to the print function. That's what I want you to do, such that the output looks like line 13 looks like Elon Musk, so it looks identical as before. But you must simply add yourself a third output and put in text that you need.
###### BILAL NOORGAT

Okay, so add a new item to the print function. So basically in line twelve, right?
###### THOMAS LEIGH

No. So if you look on line seven, you can see my highlight.
###### BILAL NOORGAT

Yes.
###### THOMAS LEIGH

Text was separated by a comma. Then we have this. So I want you to add another comma and put in a new value that's essentially what I'm asking of you.
###### BILAL NOORGAT

Okay, put a comma. And then do what? Sorry, I didn't hear you.
###### THOMAS LEIGH

And then basically put in text such that the output looks like line 13.
###### BILAL NOORGAT

Oh, okay, I see. Should I run it?
###### THOMAS LEIGH

Yes.
###### BILAL NOORGAT

Wait. Okay, perfect.
###### THOMAS LEIGH

Now I want you to copy that and paste it on all of the lines.
###### BILAL NOORGAT

Okay.
###### THOMAS LEIGH

It'S not running.
###### BILAL NOORGAT

Okay, I see.
###### THOMAS LEIGH

So we're now going to, now let's compare some of their fortunes. Is Elon richer than Bernard?
###### BILAL NOORGAT

False. Okay. Is the difference more than 50 billion? Let me run this and see. True. Okay, can I log something?
###### THOMAS LEIGH

Yes.
###### BILAL NOORGAT

Let me just tell it not to answer. I'm looking at a line of code. It reads print. And in parentheses there is some text, and there's a comma after the text with a formula that reads 251 greater than 200. And after running this code, it reads the word true. I understand 251 is greater than 200. That's a true statement. But why does it give me the text true? What if I want something else instead of the word true? Okay.
###### THOMAS LEIGH

So again, then, if we're going to just swap these around, you can also see that I'm going to click and drag over this and comment all of it. You can notice that if you click and drag over code, you can comment and uncomment multiple lines at once.
###### BILAL NOORGAT

I see.
###### THOMAS LEIGH

I'm going to run it again, and I'm going to go further now and I'm going to print ten plus ten equals.
###### BILAL NOORGAT

Okay, so for this one here, let me log something quickly. I'm looking at a line of code. It starts with print, and within the parentheses there is a formula. Ten plus ten equals equals. So there's two equal equal signs. And then the number 20.
###### THOMAS LEIGH

When you.
###### BILAL NOORGAT

Run it says true. My question is, why are there two equal signs and not one like what we normally see in mathematics?
###### THOMAS LEIGH

Excellent. Excellent question. Okay, I want you to run the code when we put in one. See, I put in one.
###### BILAL NOORGAT

Aha.
###### THOMAS LEIGH

So I don't expect you to understand that right now. That's part of our next lesson.
###### BILAL NOORGAT

Okay.
###### THOMAS LEIGH

Introduced to the assignment operator, and we're introduced to variables. And just to help you understand, if you look at lines five to ten, it is not. As a programmer and someone who's into automation as a programmer, you build applications and you automate things. To have a string that's identical on every line that you must write out manually, there's a more efficient way to do it, and it's called variables.
###### BILAL NOORGAT

I see.
###### THOMAS LEIGH

It's just good old african rain. Okay. Yes. I think this is. I don't want to introduce new information here. Don't want to introduce new information. But I think we're learning a lot here. The way that we're going to end this lesson off is, I'm going to say that we learned about text, we learned about the print function, we learned about numbers, and we learned about pemdas. Okay? And then we also learned about true and false, very briefly, learned about true and false. So in Python, the terminology for these different types of data is called a string. It's called an integer, and it's called a boolean. I don't know if you have any experience with boolean logic, which is a mathematics term.
###### BILAL NOORGAT

No, but I do remember these terms from that c plus plus years ago.
###### THOMAS LEIGH

Yes. And then we learned about some basic arithmetic operators, and part of that was we learned about plus minus, divide, multiply. We also learned about exponents and, yes, exponents and modulus. Modulus. And then the last thing that we learned about is y double equals and not single equals. That's everything that we learned in this lesson. I hope you are not too exhausted or mind fried. I promise you that a simple investment in the fundamentals will provide, will give dividends for the rest of your life. Genuinely, for the rest of your life. Say again?
###### BILAL NOORGAT

I appreciate this, and thank you. I do believe the foundation is very important.
###### THOMAS LEIGH

Good. It's a pleasure, pleasure, pleasure working with you. I want to show you now, before we, if you look at the code folder for one last time on main py from lines five until 27, you can. Yes, the colors are teaching you something. Okay. The different colors, the green are your comments and your strings, or the text, which are orange. I guess replica doesn't have the best color differentiation, but I'm very happy that we can end our first lesson with you being able to now look at code and be able to differentiate between what the different types of data are. In Python that you get your text and integers, which are your simple numbers, have your arithmetic operators that are all calculated into a single expression by your computer, and then a brief introduction into your true and false. But we're going to get into that next week. Thank you for your time. Thank you for being such a good student. What I need you to do for me is I need you to take the conversation that you've had thus far. You've had one long one, or perhaps two, however many chats you've had. I need you to click on the top and click chat, and you need to share, and then you need to share the link with me.
###### BILAL NOORGAT

Okay, sure. 1 second. Let me do that.
###### THOMAS LEIGH

Now that would help me.
###### BILAL NOORGAT

Can I send it to you via link?
###### THOMAS LEIGH

Paste it in the zoom chat if you can.
###### BILAL NOORGAT

See if that works.
###### THOMAS LEIGH

Loading for me? Yes. Perfect.
###### BILAL NOORGAT

Okay. And this file that we worked on today, can I save this or. No need.
###### THOMAS LEIGH

So you'll always have access to it. You can return to replit and it's shared with you.
###### BILAL NOORGAT

Okay, cool.
###### THOMAS LEIGH

So it's already saved. It'll be on your replit account that you can return. Okay.
###### BILAL NOORGAT

All right. Do you recommend having a session like this once a week?
###### THOMAS LEIGH

Okay. So it depends how fast you learn. I think a great place to start is one lesson a week. Yeah. Because I know that you are a working person, so you're busy, but it's some homework. The homework really comes down to just solidifying what we learned in the class. I'm providing you with the material and it's really mostly going to be based conversationally so that I can test your understanding. So we will see.
###### BILAL NOORGAT

Okay, let's keep it once a week and then we see how it goes. Because, yeah, I do have many other projects I am busy with.
###### THOMAS LEIGH

Okay. We have a couple of students that do two lessons a week, one on Monday and one on Friday.
###### BILAL NOORGAT

Okay.
###### THOMAS LEIGH

And I think once we get the ball rolling, you can decide what's going to be most efficient for you.
###### BILAL NOORGAT

Sure, sounds good.
###### THOMAS LEIGH

Great. All right.
###### BILAL NOORGAT

Thank you so much, Thomas. Thank you, Timbani. Really appreciate you guys time and efforts. Please send me the invoice and then I can sort out the payments via bank transfer.
###### THOMAS LEIGH

All right.
###### BILAL NOORGAT

Okay, thanks.
###### THOMAS LEIGH

We're going to send you some probably by tomorrow given that it's quite late to aside, we'll send you some maybe the recorded end of this lecture and we'll send you some homework and look forward to speaking to you soon.
###### BILAL NOORGAT

Likewise. Take care, guys. Bye bye.
###### THOMAS LEIGH

Cheers. Bye.
