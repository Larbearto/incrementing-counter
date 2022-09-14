So now we're going to make this function by having it count up to whatever this data target is, and

we want to put it in here.

So basically the inner text of counter, so we have multiple counters.

That means that we need to bring it in with query, select or all.

So let's say const counters set that to document Dot's query select are all all the classes of counter.

And that's going to give us a node list which is similar to an array.

So we want to then loop through that with a for each for each takes in a function.

So we'll say for each counter, then let's first of all take the counter so that that specific element

and let's set the inner text to zero and I'm going to set it to a string of zero.

So now it's going to just show zero in inside of the div right here.

So that's inner text.

We'll either you can either put something in there like we are now or you can get something from it

with inner text.

So I'm going to have a function in here called update counter and this is going to be an arrow function

and then we want to get the target.

So let's say target, which is in the data target attribute so we can take the counter and we can call

dot get attribute.

And the attribute we want to get is going to be data dash target.

Now this is going to be a string.

In fact, I'll go ahead and console.log and I'm going to use the type of operator and show you what

data type target is also the value of target.

So if I go down here and I open up my console, actually nothing is going to show because we haven't

called this.

We want to call it.

So outside of update counter, we'll call update counter and it's going to just call it once and we're

going to see the type which is a string and then whatever the data target is now to change this to a

number, which is what I want to do because we're going to want to do some math on it.

We could either wrap it in a number constructor, we could use Parse INT, or we can just add a plus

sign.

So if we save that now, you can see down here that turns it into a number.

So let's get rid of this and let's create another variable called see.

And this is going to be whatever is in the inner text.

We set it to zero here, but now we want to get it.

So let's say counter inner text and we want that to be a number as well.

So I'm just going to add a plus sign here and then we're going to create the increment.

So we need to decide how how much do we want to increment this by.

And depending on that number, that will depend on how fast or slow it is.

So we want the target.

Let's take the target and let's divide by.

And this could be anything you want.

If we divide it by if we just use target, it's just going to it's going to increment by itself.

So 12,000, 5000.

And it'll just basically just flick right on the screen.

We want it to count upwards.

So I'm going to divide it by 200 and you can experiment with this if you want.

Now I'm going to console.log increment here.

So the first one, remember this is 1200 and that divided by 200 would be 65,000 by 225 7503, 7330

7.5.

So let's go ahead and add an if statement here.

We want to make sure that that C number we want to make sure that that is less than the target because

we don't want to go past the target.

So if it is, then let's take the counter and let's set the inner text and I'm going to set that to

a set of back ticks and we want to take that C and we want to add whatever that increment is.

But I also want to round this up.

So let's, let's do math dot seal.

So math dot seal is going to round this number up.

Okay.

Now if I save that, you can see we get 60, 25, 38, which I just saw on the console.

It was 37.5.

But we're rounding it up now.

We want this not to just stop on the first increment.

We want it to keep going until until it reaches this this right here.

So we need to keep calling update counter.

Now, if we just call it like this, it's not going to work.

I mean, it's going to go up, but it's not going to do that.

The count up, the animation type effect.

So what we want to do is just pass this in a set time out and we want to run it, let's say, every.

We are not every, but we want to wait one millisecond before we run it that way.

It waits that millisecond, which gives it time, and then it will go ahead and keep running.

And it's incrementing by 60, 25, 38, whatever it was.

And if you want it to go slower, you could do you can make this a bigger number like 1000 and you can

see that takes longer if we do, let's say ten very quick.

So it's up to you on how fast you want to make this.

I think 200 is good.

And then I just want to put an LZ here.

So else then let's just set the counter dot in our text and we'll set it directly to whatever the target

is because we obviously we don't want it to go above these numbers which are in the target, and that's

pretty much it.

So obviously if you wanted to change this, if you want it to do, you know, 500,000 and save, it's

going to it's even though this is this number's way higher than these, it's still going to take the

same amount of time.

It's not like these will finish first and then this is going to finish after because we took whatever

the target is and we divide it by a specific number and then it's going to increment by that.

So you can set these to absolutely anything.

All right.

So I hope that made sense.

And of course, you could add this to your website, just a little widget and it doesn't have to be

followers or it can be any number at all.

And it's pretty easy to to implement.

So no jQuery or anything like that.

But that's it.
