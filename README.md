# Challenge Time

## Introduction
Two words are friends if they have a Levenshtein distance of 1. That is, you
can add, remove, or substitute exactly one letter in word X to create word Y.
A word’s social network consists of all of it's friend, all of it's friends friends, and all of it's friends friends friends.

## Problem
Write a program in your favorite dynamic language that efficiently finds the
social network for any given word, using the word list provided.

## Solution
The solution is in the getSocialNetwork() method of networker.js. It has been implemented in JavaScript.
The openDictionary() method must also be called to read the wordlist file into memory. index.html demonstrates use of the code.

This can be found running on http://amwj.github.io/WayPaver/.