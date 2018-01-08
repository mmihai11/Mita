Folosind template-uri, implementati o clasa Stack care poate fi folosita pentru stocarea itemilor de orice tip. Nu trebuie sa implementati constructori/destructori, cei default sunt suficienti. Nu trebuie sa folositi new. Clasa trebuie sa suporte urmatoarele functii publice (se presupune ca T este tipul parametrizat pe care il stocheaza Stack):
•bool Stack::empty() – returneaza daca stiva este goala
•void Stack::push(const T &item) – adauga item la stiva
•T &Stack::top() – returneaza referinta catre cel mai recent adaugat item
•void Stack::pop() – scoate din stiva itemul cel mai recent adaugat
Folositi din STL un vector, deque sau list pentru implementare Stack (nu se foloseste clasa stack din STL). Faceti functiile membre const unde este nevoie. In cazul in care stiva este goala, pop nu trebuie sa faca nimic, si top se comporta normal (eroare).
Cand lucrati cu clase template, nu puteti sa separati implementarile functiilor in fisiere .cpp separate. Puneti tot codul in definitia clasei.
