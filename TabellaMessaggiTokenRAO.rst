**Tabella messaggi token R.A.O. pubblico** **inviati dall’IdP**
===============================================================

============= ============ ======================================================================================================================== =========== ================= ======================================= =======================================
Type          responseCode responseMessage                                                                                                          Codice HTTP inviate al R.A.O. inviate all’utente modello a) 3.6 LL GG inviate all’utente modello b) 3.6 LL GG
============= ============ ======================================================================================================================== =========== ================= ======================================= =======================================
Ok            1            richiesta autorizzata\ ,token correttamente ricevuto.                                                                    200         SI                NO                                      SI
User Exists   2            spiacenti, per questo utente risulta già rilasciata un’identità digitale SPID.                                           403         SI                NO                                      SI
Unauthorized  3            spiacenti, la richiesta non è stata autorizzata in quanto è impossibile identificare l’autore del token.                 401         SI                NO                                      SI
Bad Request   4            spiacenti, il token non è utilizzabile in quanto danneggiato.                                                            400         SI                NO                                      SI
Token Exists  5            l’attuale richiesta è andata a buon fine sostituendo la precedente.                                                      201         SI                NO                                      SI
Invalid Token 6            spiacenti, è stato superato il numero massimo di tentativi di inserimento della passphrase .                             403         NO                SI                                      SI
expired token 7            spiacenti, sono passati più di 30 giorni dall’identificazione presso la P.A., il token è scaduto e non più utilizzabile. 403         NO                SI                                      SI
generic error 100          spiacenti,si è verificato un errore.                                                                                     403         SI                SI                                      SI
============= ============ ======================================================================================================================== =========== ================= ======================================= =======================================

.. |image0| image:: media/image1.png
   :width: 2.11979in
   :height: 1.03612in
