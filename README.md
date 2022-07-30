www.patika.dev
# patika-proje3

  Proje 3
  [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

  Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

    - Root(kök) değerimiz 7
                                  
                7           - 1. adım: Root(kök) değerimiz 7
              /   \         - 2. adım: 5 değeri root değeri olan 7'den küçük olduğu için düğümün solunda bulunur.
            5       8       - 3. adım: 1 değeri root değeri 7'den küçük ve node değer olan 5'ten de küçük olduğu için 5'in solunda bulunur.
          /   \       \     - 4. adım: 8 değeri root değeri 7'den büyüktür. Bu yüzden root değerinin sağında yer alır.
        1      6        9   - 5. adım: 3 değeri node değeri 1'den büyük olduğu için sağında yer alır.
      /   \                 - 6. adım: 6 değeri root 7'den küçük ama node 5'ten büyük olduğu için 5 düğümünün 
     0     3                - 7. adım: 0 değeri 1 düğümünden küçük olduğu için solunda yer alır. Aynı zamanda arrayin minimum değeridir.       
         /   \              - 8. adım: 9 değeri node değeri 8'den büyük olduğu için sağında yer alır. Aynı zamanda arrayin maksimum değeridir.
        2     4             - 9. adım: 4 değeri node değeri 3'ten büyük olduğu için sağında yer alır.  
                            - 10. adım: 2 değeri 3 düğümünden küçük olduğu için solunda yer alır.
     
     
