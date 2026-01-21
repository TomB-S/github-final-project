#!/bin/bash
# Ce script calcule l'intérêt simple.
# Auteur : TomB-S

echo "Entrez le capital :"
read p
echo "Entrez le taux d'intérêt annuel :"
read r
echo "Entrez la durée (en années) :"
read t

s=`expr $p \* $t \* $r / 100`
echo "L'intérêt simple est : "
echo $s
