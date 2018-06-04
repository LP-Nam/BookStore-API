# DANH SÁCH API ĐÃ TẠO

* METHOD - URL:
    * GET  ***/api/product/new*** lấy danh sách sản phẩm mới nhất.
    * GET  ***/api/product/best-seller*** lấy danh sách sản phẩm bán chạy nhất.
    * GET  ***/api/product/:productID*** lấy 1 sản phẩm theo mã sản phẩm
    * GET ***/api/product/publisher/:publisherID*** lấy danh sách sản phẩm theo nhà xuất bản
    * GET ***/api/product/category/:categoryID*** lấy danh sách sản phẩm theo loại sản phẩm
    * GET ***/api/product/publisher*** tìm các nhà xuất bản
    * GET ***/api/product/type*** tìm các thể loại
    * GET ***/api/checkUsername/:username*** kiểm tra tài khoản có tồn tại

    * GET ***/api/countProduct*** số lượng sách chưa bị xóa
    * GET ***/api/product/publisher/countAllBook/:publisherID*** lấy số lượng sách theo nhà xuất bản

    * POST ***/api/product/publisherTestPaging/:publisherID*** lấy danh sách sản phẩm theo nhà xuất bản

    * POST ***/api/product/related*** tìm các thể loại theo mã sách
    * POST ***/api/product/publisher*** thêm mới 1 hãng sản xuất
    * POST ***/api/product/category*** thêm mới 1 loại sản phẩm
    * POST ***/api/product*** thêm mới 1 sản phẩm
    * POST ***/api/register*** thêm 1 tài khoản mới
    * POST ***/api/checkUsername*** kiểm tra tài khoản có tồn tại