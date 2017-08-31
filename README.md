public static int [][] TurnRight (int [][] array2D) {
                
                               int [][] localArray2D = new int [4][4];
                               
                               for (int i = 0; i < array2D.length; i++) {
                                               for (int k = array2D[0].length - 1; k > -1; k--) {

                                                               localArray2D[i][(array2D[0].length - k -1)] = array2D[k][i];
                
                                               }
                               }
                               
                               return localArray2D;
                }
