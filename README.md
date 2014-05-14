http://www.eyecon.ro/bootstrap-datepicker/ Bootstrap Datepicker with locales.

    <script type="text/javascript" src="js/bootstrap-datepicker.js"></script>
    <script type="text/javascript" src="js/locales/bootstrap-datepicker.tr.js" charset="UTF-8"></script>
    
<h4>Locale example</h4>

    ;(function($) {
        $.fn.datepicker.DPGlobal.dates['tr'] = {
            days: ["Pazar", "Pazartesi", "Salı", "Çarşamba", "Perşembe", "Cuma", "Cumartesi", "Pazar"],
            daysShort: ["Pz", "Pzt", "Sal", "Çrş", "Prş", "Cu", "Cts", "Pz"],
            daysMin: ["Pz", "Pzt", "Sa", "Çr", "Pr", "Cu", "Ct", "Pz"],
            months: ["Ocak", "Şubat", "Mart", "Nisan", "Mayıs", "Haziran", "Temmuz", "Ağustos", "Eylül", "Ekim", "Kasım", "Aralık"],
            monthsShort: ["Oca", "Şub", "Mar", "Nis", "May", "Haz", "Tem", "Ağu", "Eyl", "Eki", "Kas", "Ara"]
        };
    }(jQuery));

<h4>Usage</h4>

    $('input').datepicker({
        format: 'yyyy-mm-dd',
        language:"tr"
    });
