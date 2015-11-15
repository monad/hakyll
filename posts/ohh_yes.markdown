----
title: OHH YES 
date: 2015-11-14 23:48:22
author: Patchouli 
----

```
{-# LANGUAGE UnicodeSyntax #-}
{-# LANGUAGE TypeOperators #-}
module Mettaton where

data (👠) = Kiss
  deriving (Read, Show)

(📺) :: (👠)
(📺) = (👄)
  where (👄) = Kiss

main :: IO ()
main = print (📺)
```
