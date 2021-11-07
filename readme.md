## About <a href="javascript:void();" target="_blank">Laravel Delete Sweet Alert Popup Components</a>

Delete Sweet Alert Popup Components For Laravel Project

## Doc:

<hr/>

- first copy plugins and js folder then paste it on public folder

- Then Link those Js and css file to your layouts/app.blade

  - For Css
     ```
     <link rel="stylesheet" href="{{ asset('plugins/sweet-alert2/sweetalert2.min.css') }}">
     ```
  - For Js
    ```
    <script src="{{asset('plugins/sweet-alert2/sweetalert2.min.js')}}"></script>
    <script src="{{asset('js/delete.js')}}"></script>
    ```

- then copy components/delete.blade.php and paste it on resource/views/components folder.

- For use This Componet use those Line to your file

  ```
  <a href="javascript:void();" onclick="delete_action({{ route('user.delete',$user->id) }})"></a>
  ```

  ```
  {{-- call It for once time --}}
  <x-delete>
  ```



## <a href="https://iqbalhasan.dev" target="_blank">iqbalhasan.dev</a> Sponsors

We would like to extend our thanks to the following sponsors for funding <a href="https://iqbalhasan.dev" target="_blank">iqbalhasan.dev</a> development. If you are interested in becoming a sponsor, please email us <a href="mailto:info@iqbalhasan.dev">info@iqbalhasan.dev</a>

## Security Vulnerabilities

If you discover a security vulnerability within Laravel, please send an e-mail to <a href="https://iqbalhasan.dev" target="_blank">IQBAL HASAN</a> via [info@iqbalhasan.dev](mailto:info@iqbalhasan.dev). All security vulnerabilities will be promptly addressed.

## License

The iqbalhasan.dev Project is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).

