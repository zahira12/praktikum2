# praktikum2
	
- Latihan 1 membuat penentuan terbesar dari 3 bilangan. 
	* mendeklarasikan variabel int a,b,c sebagai variabel input
	* menginputkan nilai a,b,c
	* membandingkan nilai a,b,c dengan rumus if berikut kodenya
	
if (A>B){

       		if (A>C)

       		 cout<< "Bilangan Terbesar Adalah :" << A;

       		else

        	cout<< "Bilangan Terbesar Adalah :" << C;

        }else{

        	if ( B>C )

        	cout << "Bilangan Terbesar Adalah:" << B;

       		 else

        	cout << "Bilangan Terbesar Adalah:" << C;


2. ini hasilnya
	![img](https://github.com/zahira12/praktikum2/blob/master/latihan1/hasil%201%20Screenshot.png)
	![img](https://github.com/zahira12/praktikum2/blob/master/latihan1/hasil%202%20Screenshot.png)
	![img](https://github.com/zahira12/praktikum2/blob/master/latihan1/hasil%203%20Screenshot.png)

3..Latihan2 membuat penentuan terbesar dan terkecil dari 4 variabel. -Mendeklarasikan variabel n,nilai sebagai variabel input -Mendeklarasikan variabel i sebagai pembatas inputan/perulangan -Mendeklarasikan max sebagai nilai terbesar dan min nilai terkecil -Menginputkan nilai n dimana menunjukan banyak angka yang akan di input -menginputkan nilai nilai yang akan di bandingkan. Berikut kode lengkapnya

	int i,n,max,min,nilai;

		cout<<"===Menentukan Bilangan Terbesar & Terkecil==="<< endl;
   		cout<<"Masukan Banyak Bilangan:";
   		 cin>> n;
    		cout<<"Masukan Nilai ke =";
    		cin>> nilai;

		max=nilai;
		min=nilai;

 		for(i=2;i<=n;i++) //dapat dibaca i akan membaca di nilai ke2 dimana i kurang dari samadengan n,i akan menambah 1 angka dan seterusnya.
    		{

        		cout<<"Masukan Nilai Ke"<<i<<"=";
       	 		cin>>nilai;

      		 	 if (nilai>max) max=nilai;
       			 if (nilai<min) min=nilai;
	}
    	cout<<"Nilai Terbesar Adalah:" <<max<<"\nNilai Terkecil Adalah:"<<min;

4. ini hasilnya
	![img](https://github.com/zahira12/praktikum2/blob/master/latihan2/hasil%204%20Screenshot.png)
	![img](https://github.com/zahira12/praktikum2/blob/master/latihan2/hasil%205%20Screenshot.png)
	![img](https://github.com/zahira12/praktikum2/blob/master/latihan2/hasil%206%20Screenshot.png)
	![img](https://github.com/zahira12/praktikum2/blob/master/latihan2/hasil%207%20Screenshot.png)
