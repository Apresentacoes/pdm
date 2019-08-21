Nativo
AlertDialog.Builder builder = new AlertDialog.Builder(MainActivity.this);
  builder.setTitle("ALERTA !!");
  builder.setMessage("CADASTRADO COM SUCESSO !");
  builder.setCancelable(false);
  builder.setPositiveButton("Sim", new DialogInterface.OnClickListener() {
      @Override
      public void onClick(DialogInterface dialogInterface, int i) {
   }
  });
  builder.setNegativeButton("Não", new DialogInterface.OnClickListener() {
      @Override
      public void onClick(DialogInterface dialogInterface, int i) {

   }
  });
  builder.create().show();
  
  Sweet
  // Mostra a mensagem de erro.
new SweetAlertDialog(LoginActivity.this, SweetAlertDialog.ERROR_TYPE)
 .setTitleText("Erro")
 .setContentText(responseError.getMensagem())
 .setConfirmClickListener(new SweetAlertDialog.OnSweetClickListener() {
 @Override
 public void onClick(SweetAlertDialog sweetAlertDialog) {
    sweetAlertDialog.dismissWithAnimation();
  }
 }).show();
implementation 'com.github.thomper:sweet-alert-dialog:v1.4.0'
                
                
