# firstrepository
## Overview
The first step was to **create the repository**, and tick the box to add a README. You can then edit it to your liking! :)
## 04/10/2022
object WhatLearnt extends App{
  // Tuples
  val tuple = Map(24 -> "Tuples")

  // For Loop & Lists
  val list = List("F", "o", "r", " ", "L", "o", "o", "p", "s")
  var listFinal = ""
  for(i <- list){
    listFinal += i;
  }

  // While Loops
  var value = 1
  var whileList = ""
  while(value < 2){
    whileList += "While Loops"
    value += 1
  }

  // Match Expressions
  val number = 29
  var matchList = ""
  number match{
    case 20 => matchList += "Wrong"
    case 24 => matchList += "Wrong again..."
    case 23 => matchList += "Bruh"
    case 18 => matchList += "lol"
    case 29 => matchList += "Match Expressions"

    // If no other cases match:
    case _ => matchList += "ZzzzZzzzzZ"
  }

  val whatILearnt = List(tuple.get(24),"Lists",listFinal,whileList,matchList)
  for(i <- whatILearnt){
    println("I have Learnt: " + i);
  }
}
