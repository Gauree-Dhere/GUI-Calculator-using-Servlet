//b1 variable name for JButton1
//t1 variable name for JTextfield1


public class GUI_Servlet_Calculator extends javax.swing.JFrame 
{
    double firstnumber;
    double secondnumber;
    double result;
    String operator;
    
    public GUI_Servlet_Calculator() 
    {
        initComponents();
    }
    @SuppressWarnings("unchecked")
    // <editor-fold defaultstate="collapsed" desc="Generated Code">                          
    private void initComponents() {

        jPanel1 = new javax.swing.JPanel();
        t1 = new javax.swing.JTextField();
        jPanel2 = new javax.swing.JPanel();
        jPanel3 = new javax.swing.JPanel();
        b1 = new javax.swing.JButton();
        b2 = new javax.swing.JButton();
        b3 = new javax.swing.JButton();
        b4 = new javax.swing.JButton();
        b5 = new javax.swing.JButton();
        b6 = new javax.swing.JButton();
        b7 = new javax.swing.JButton();
        b8 = new javax.swing.JButton();
        b9 = new javax.swing.JButton();
        b0 = new javax.swing.JButton();
        bdel = new javax.swing.JButton();
        bclr = new javax.swing.JButton();
        ba = new javax.swing.JButton();
        bs = new javax.swing.JButton();
        bm = new javax.swing.JButton();
        bd = new javax.swing.JButton();
        bdot = new javax.swing.JButton();
        bequ = new javax.swing.JButton();

        setDefaultCloseOperation(javax.swing.WindowConstants.EXIT_ON_CLOSE);

        jPanel1.setBackground(new java.awt.Color(204, 255, 255));
        jPanel1.setLayout(new org.netbeans.lib.awtextra.AbsoluteLayout());
        jPanel1.add(t1, new org.netbeans.lib.awtextra.AbsoluteConstraints(30, 10, 449, 57));

        jPanel2.setLayout(new org.netbeans.lib.awtextra.AbsoluteLayout());

        jPanel3.setBackground(new java.awt.Color(204, 255, 255));

        b1.setText("1");
        b1.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                b1ActionPerformed(evt);
            }
        });

        b2.setText("2");
        b2.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                b2ActionPerformed(evt);
            }
        });

        b3.setText("3");
        b3.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                b3ActionPerformed(evt);
            }
        });

        b4.setText("4");
        b4.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                b4ActionPerformed(evt);
            }
        });

        b5.setText("5");
        b5.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                b5ActionPerformed(evt);
            }
        });

        b6.setText("6");
        b6.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                b6ActionPerformed(evt);
            }
        });

        b7.setText("7");
        b7.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                b7ActionPerformed(evt);
            }
        });

        b8.setText("8");
        b8.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                b8ActionPerformed(evt);
            }
        });

        b9.setText("9");
        b9.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                b9ActionPerformed(evt);
            }
        });

        b0.setText("0");
        b0.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                b0ActionPerformed(evt);
            }
        });

        bdel.setText("Del");
        bdel.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                bdelActionPerformed(evt);
            }
        });

        bclr.setText("Clear");
        bclr.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                bclrActionPerformed(evt);
            }
        });

        ba.setText("+");
        ba.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                baActionPerformed(evt);
            }
        });

        bs.setText("-");
        bs.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                bsActionPerformed(evt);
            }
        });

        bm.setText("*");
        bm.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                bmActionPerformed(evt);
            }
        });

        bd.setText("/");
        bd.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                bdActionPerformed(evt);
            }
        });

        bdot.setText(".");
        bdot.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                bdotActionPerformed(evt);
            }
        });

        bequ.setText("=");
        bequ.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                bequActionPerformed(evt);
            }
        });

        javax.swing.GroupLayout jPanel3Layout = new javax.swing.GroupLayout(jPanel3);
        jPanel3.setLayout(jPanel3Layout);
        jPanel3Layout.setHorizontalGroup(
            jPanel3Layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
            .addGroup(jPanel3Layout.createSequentialGroup()
                .addGroup(jPanel3Layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
                    .addGroup(jPanel3Layout.createSequentialGroup()
                        .addContainerGap()
                        .addGroup(jPanel3Layout.createParallelGroup(javax.swing.GroupLayout.Alignment.TRAILING)
                            .addComponent(bd)
                            .addGroup(jPanel3Layout.createSequentialGroup()
                                .addGroup(jPanel3Layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
                                    .addGroup(jPanel3Layout.createSequentialGroup()
                                        .addComponent(b1)
                                        .addGap(18, 18, 18)
                                        .addComponent(b2)
                                        .addGap(18, 18, 18)
                                        .addComponent(b3))
                                    .addGroup(jPanel3Layout.createSequentialGroup()
                                        .addComponent(b4)
                                        .addGap(18, 18, 18)
                                        .addComponent(b5)
                                        .addGap(18, 18, 18)
                                        .addComponent(b6))
                                    .addGroup(jPanel3Layout.createSequentialGroup()
                                        .addComponent(b7)
                                        .addGap(18, 18, 18)
                                        .addComponent(b8)
                                        .addGap(18, 18, 18)
                                        .addComponent(b9)))
                                .addGap(48, 48, 48)
                                .addGroup(jPanel3Layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
                                    .addGroup(jPanel3Layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
                                        .addComponent(ba)
                                        .addComponent(bs, javax.swing.GroupLayout.Alignment.TRAILING))
                                    .addGroup(jPanel3Layout.createSequentialGroup()
                                        .addGap(4, 4, 4)
                                        .addComponent(bm))))
                            .addGroup(javax.swing.GroupLayout.Alignment.LEADING, jPanel3Layout.createSequentialGroup()
                                .addComponent(b0)
                                .addGap(18, 18, 18)
                                .addComponent(bdot)
                                .addGap(18, 18, 18)
                                .addComponent(bdel))
                            .addComponent(bclr, javax.swing.GroupLayout.Alignment.LEADING, javax.swing.GroupLayout.PREFERRED_SIZE, 73, javax.swing.GroupLayout.PREFERRED_SIZE)))
                    .addGroup(jPanel3Layout.createSequentialGroup()
                        .addGap(94, 94, 94)
                        .addComponent(bequ, javax.swing.GroupLayout.PREFERRED_SIZE, 75, javax.swing.GroupLayout.PREFERRED_SIZE)))
                .addContainerGap(36, Short.MAX_VALUE))
        );
        jPanel3Layout.setVerticalGroup(
            jPanel3Layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
            .addGroup(jPanel3Layout.createSequentialGroup()
                .addGap(31, 31, 31)
                .addGroup(jPanel3Layout.createParallelGroup(javax.swing.GroupLayout.Alignment.BASELINE)
                    .addComponent(b1)
                    .addComponent(b2)
                    .addComponent(b3)
                    .addComponent(ba))
                .addGap(26, 26, 26)
                .addGroup(jPanel3Layout.createParallelGroup(javax.swing.GroupLayout.Alignment.BASELINE)
                    .addComponent(b4)
                    .addComponent(b5)
                    .addComponent(b6)
                    .addComponent(bs))
                .addGap(18, 18, 18)
                .addGroup(jPanel3Layout.createParallelGroup(javax.swing.GroupLayout.Alignment.BASELINE)
                    .addComponent(b7)
                    .addComponent(b8)
                    .addComponent(b9)
                    .addComponent(bm))
                .addGap(18, 18, 18)
                .addGroup(jPanel3Layout.createParallelGroup(javax.swing.GroupLayout.Alignment.BASELINE)
                    .addComponent(b0)
                    .addComponent(bd)
                    .addComponent(bdot)
                    .addComponent(bdel))
                .addGap(18, 18, 18)
                .addGroup(jPanel3Layout.createParallelGroup(javax.swing.GroupLayout.Alignment.BASELINE)
                    .addComponent(bclr)
                    .addComponent(bequ))
                .addContainerGap(44, Short.MAX_VALUE))
        );

        jPanel2.add(jPanel3, new org.netbeans.lib.awtextra.AbsoluteConstraints(120, -10, 290, 270));

        javax.swing.GroupLayout layout = new javax.swing.GroupLayout(getContentPane());
        getContentPane().setLayout(layout);
        layout.setHorizontalGroup(
            layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
            .addGroup(layout.createSequentialGroup()
                .addGap(25, 25, 25)
                .addComponent(jPanel1, javax.swing.GroupLayout.PREFERRED_SIZE, 509, javax.swing.GroupLayout.PREFERRED_SIZE)
                .addContainerGap(javax.swing.GroupLayout.DEFAULT_SIZE, Short.MAX_VALUE))
            .addGroup(layout.createSequentialGroup()
                .addContainerGap()
                .addComponent(jPanel2, javax.swing.GroupLayout.DEFAULT_SIZE, javax.swing.GroupLayout.DEFAULT_SIZE, Short.MAX_VALUE)
                .addContainerGap())
        );
        layout.setVerticalGroup(
            layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
            .addGroup(layout.createSequentialGroup()
                .addContainerGap()
                .addComponent(jPanel1, javax.swing.GroupLayout.PREFERRED_SIZE, 80, javax.swing.GroupLayout.PREFERRED_SIZE)
                .addPreferredGap(javax.swing.LayoutStyle.ComponentPlacement.RELATED)
                .addComponent(jPanel2, javax.swing.GroupLayout.DEFAULT_SIZE, javax.swing.GroupLayout.DEFAULT_SIZE, Short.MAX_VALUE)
                .addContainerGap())
        );

        pack();
    }// </editor-fold>                        

    private void b1ActionPerformed(java.awt.event.ActionEvent evt) {                                   
        String number = t1.getText()+ b1.getText();
        t1.setText(number);
    }                                  

    private void b2ActionPerformed(java.awt.event.ActionEvent evt) {                                   
 String number = t1.getText()+ b2.getText();
        t1.setText(number);    }                                  

    private void b3ActionPerformed(java.awt.event.ActionEvent evt) {                                   
 String number = t1.getText()+ b3.getText();
        t1.setText(number);    }                                  

    private void b4ActionPerformed(java.awt.event.ActionEvent evt) {                                   
 String number = t1.getText()+ b4.getText();
        t1.setText(number);    }                                  

    private void b5ActionPerformed(java.awt.event.ActionEvent evt) {                                   
 String number = t1.getText()+ b5.getText();
        t1.setText(number);    }                                  

    private void b6ActionPerformed(java.awt.event.ActionEvent evt) {                                   
 String number = t1.getText()+ b6.getText();
        t1.setText(number);    }                                  

    private void b7ActionPerformed(java.awt.event.ActionEvent evt) {                                   
 String number = t1.getText()+ b7.getText();
        t1.setText(number);    }                                  

    private void b8ActionPerformed(java.awt.event.ActionEvent evt) {                                   
 String number = t1.getText()+ b8.getText();
        t1.setText(number);    }                                  

    private void b9ActionPerformed(java.awt.event.ActionEvent evt) {                                   
 String number = t1.getText()+ b9.getText();
        t1.setText(number);    }                                  

    private void b0ActionPerformed(java.awt.event.ActionEvent evt) {                                   
 String number = t1.getText()+ b0.getText();
        t1.setText(number);    }                                  

    private void bdotActionPerformed(java.awt.event.ActionEvent evt) {                                     
String number = t1.getText()+ bdot.getText();
        t1.setText(number);    }                                    

    private void bdelActionPerformed(java.awt.event.ActionEvent evt) {                                     
String number = t1.getText()+ bdel.getText();
        t1.setText(number);    }                                    

    private void bclrActionPerformed(java.awt.event.ActionEvent evt) {                                     
    t1.setText(" ");  
    }                                    

    private void bequActionPerformed(java.awt.event.ActionEvent evt) {                                     

        secondnumber = Double.parseDouble(t1.getText());
        if(operator == "+")
        {
            result=firstnumber+secondnumber;
            t1.setText(Double.toString(result));
        }
        else if(operator == "-")
        {
            result=firstnumber-secondnumber;
           t1.setText(Double.toString(result));
        
        }
         else if(operator == "/")
        {
            result=firstnumber/secondnumber;
            t1.setText(Double.toString(result));
        }
         else if(operator == "*")
        {
            result=firstnumber*secondnumber;
            t1.setText(Double.toString(result));
        }
    }                                    

    private void baActionPerformed(java.awt.event.ActionEvent evt) {                                   
        
        firstnumber = Double.parseDouble(t1.getText());
        t1.setText(" ");
        operator="+";
    }                                  

    private void bsActionPerformed(java.awt.event.ActionEvent evt) {                                   
firstnumber = Double.parseDouble(t1.getText());
      t1.setText(" ");
operator="-";
    }                                  

    private void bdActionPerformed(java.awt.event.ActionEvent evt) {                                   
firstnumber = Double.parseDouble(t1.getText());
      t1.setText(" ");
operator="/";
    }                                  

    private void bmActionPerformed(java.awt.event.ActionEvent evt) {                                   
firstnumber = Double.parseDouble(t1.getText());
      t1.setText(" ");
operator="*";
    }                                  
    public static void main(String args[]) 
{
   
    java.awt.EventQueue.invokeLater(new Runnable()
    {
        public void run()
        {
            new GUI_Servlet_Calculator().setVisible(true);
            }
        }
    );
    }
    // Variables declaration - do not modify                     
    private javax.swing.JButton b0;
    private javax.swing.JButton b1;
    private javax.swing.JButton b2;
    private javax.swing.JButton b3;
    private javax.swing.JButton b4;
    private javax.swing.JButton b5;
    private javax.swing.JButton b6;
    private javax.swing.JButton b7;
    private javax.swing.JButton b8;
    private javax.swing.JButton b9;
    private javax.swing.JButton ba;
    private javax.swing.JButton bclr;
    private javax.swing.JButton bd;
    private javax.swing.JButton bdel;
    private javax.swing.JButton bdot;
    private javax.swing.JButton bequ;
    private javax.swing.JButton bm;
    private javax.swing.JButton bs;
    private javax.swing.JPanel jPanel1;
    private javax.swing.JPanel jPanel2;
    private javax.swing.JPanel jPanel3;
    private javax.swing.JTextField t1;
    // End of variables declaration                   
}
