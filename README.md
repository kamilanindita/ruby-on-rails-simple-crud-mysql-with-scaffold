# ruby-on-rails-simple-crud-with-scaffold
<br><br>
## Installations <br>
1. rails new ruby-on-rails-simple-crud-with-scaffold  -d mysql <br>
2. cd ruby-on-rails-simple-crud-with-scaffold <br>
3. setting database connection <br>
4. rails generate scaffold buku penulis:string judul:string kota:string penerbit:string tahun:integer <br>
5. rake db:migrate <br>
6. setting root route,add root :to => 'bukus#index' at routes.rb
