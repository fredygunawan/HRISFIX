# HRISFIX
</div>
<!-- /.content -->
</div>
<!-- /.content-wrapper -->
<!-- Main Footer -->
<footer class="main-footer">
    <!-- To the right -->
    <div style="align=center">
        <strong>Copyright &copy; <?= date('Y'); ?></strong> PT. Sahaware Teknologi Indonesia
    </div>
</footer>
</div>
<!-- ./wrapper -->

<!-- REQUIRED SCRIPTS -->

<!-- jQuery -->
<script src="<?= base_url() ?>plugins/jquery/jquery.min.js"></script>
<!-- Bootstrap 4 -->
<script src="<?= base_url() ?>plugins/bootstrap/js/bootstrap.bundle.min.js"></script>
<!-- AdminLTE App -->
<script src="<?= base_url() ?>dist/js/adminlte.min.js"></script>
<!-- DataTables  & Plugins -->
<script src="<?= base_url() ?>plugins/datatables/jquery.dataTables.min.js"></script>
<script src="<?= base_url() ?>plugins/datatables-bs4/js/dataTables.bootstrap4.min.js"></script>
<script src="<?= base_url() ?>plugins/datatables-responsive/js/dataTables.responsive.min.js"></script>
<script src="<?= base_url() ?>plugins/datatables-responsive/js/responsive.bootstrap4.min.js"></script>
<script src="<?= base_url() ?>plugins/datatables-buttons/js/dataTables.buttons.min.js"></script>
<script src="<?= base_url() ?>plugins/datatables-buttons/js/buttons.bootstrap4.min.js"></script>
<script src="<?= base_url() ?>plugins/jszip/jszip.min.js"></script>
<script src="<?= base_url() ?>plugins/pdfmake/pdfmake.min.js"></script>
<script src="<?= base_url() ?>plugins/pdfmake/vfs_fonts.js"></script>
<script src="<?= base_url() ?>plugins/datatables-buttons/js/buttons.html5.min.js"></script>
<script src="<?= base_url() ?>plugins/datatables-buttons/js/buttons.print.min.js"></script>
<script src="<?= base_url() ?>plugins/datatables-buttons/js/buttons.colVis.min.js"></script>
<script>
$(function() {
    $("#example1").DataTable({
        "responsive": true,
        "lengthChange": false,
        "autoWidth": false,
        "buttons": ["copy", "csv", "excel", "pdf", "print", "colvis"]
    }).buttons().container().appendTo('#example1_wrapper .col-md-6:eq(0)');
    $('#example2').DataTable({
        "paging": true,
        "lengthChange": false,
        "searching": false,
        "ordering": true,
        "info": true,
        "autoWidth": false,
        "responsive": true,
    });
});
</script>
</body>

</html>
