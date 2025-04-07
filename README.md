{
  "openapi": "3.0.1",
  "thông tin": {
    "title": "API CVRF của MSRC",
    "phiên bản": "v3"
  },
  "đường dẫn": {
    "/csaf/{mã}": {
      "lấy": {
        "thẻ": [
          "Csaf"
        ],
        "tham số": [
          {
            "tên": "id",
            "trong": "đường dẫn",
            "bắt buộc": đúng,
            "sơ đồ": {
              "kiểu": "chuỗi"
            }
          }
        ],
        "phản hồi": {
          "200": {
            "description": "Thành công"
          }
        }
      }
    },
    "/cvrf/{mã}": {
      "lấy": {
        "thẻ": [
          "Cvrf"
        ],
        "summary": "Nhận thông tin chi tiết về bản cập nhật bảo mật theo định dạng CVRF",
        "description": "Nhận bản cập nhật bảo mật chi tiết của Microsoft, được định dạng theo [Common Vulnerability Reporting\r\nFramework](http://www.icasi.org/cvrf/). MSRC điều tra tất cả các báo cáo về\r\nlỗi bảo mật ảnh hưởng đến các sản phẩm và dịch vụ của Microsoft và cung cấp các bản cập nhật này như một phần của\r\nnnỗ lực liên tục nhằm giúp bạn quản lý rủi ro bảo mật và giúp bảo vệ hệ thống của bạn.",
        "tham số": [
          {
            "tên": "id",
            "trong": "đường dẫn",
            "description": "ID tài liệu CVRF (năm-mmm)",
            "bắt buộc": đúng,
            "sơ đồ": {
              "kiểu": "chuỗi"
            }
          }
        ],
        "phản hồi": {
          "200": {
            "description": "Thành công"
          }
        }
      }
    },
    "/cvrf({mã})": {
      "lấy": {
        "thẻ": [
          "Cvrf"
        ],
        "summary": "Nhận thông tin chi tiết về bản cập nhật bảo mật theo định dạng CVRF",
        "description": "Nhận bản cập nhật bảo mật chi tiết của Microsoft, được định dạng theo [Common Vulnerability Reporting\r\nFramework](http://www.icasi.org/cvrf/). MSRC điều tra tất cả các báo cáo về\r\nlỗi bảo mật ảnh hưởng đến các sản phẩm và dịch vụ của Microsoft và cung cấp các bản cập nhật này như một phần của\r\nnnỗ lực liên tục nhằm giúp bạn quản lý rủi ro bảo mật và giúp bảo vệ hệ thống của bạn.",
        "tham số": [
          {
            "tên": "id",
            "trong": "đường dẫn",
            "description": "ID tài liệu CVRF (năm-mmm)",
            "bắt buộc": đúng,
            "sơ đồ": {
              "kiểu": "chuỗi"
            }
          }
        ],
        "phản hồi": {
          "200": {
            "description": "Thành công"
          }
        }
      }
    },
    "/./$siêu dữ liệu": {
      "lấy": {
        "thẻ": [
          "Siêu dữ liệu"
        ],
        "operationId": "./$metadata",
        "phản hồi": {
          "200": {
            "description": "Thành công",
            "nội dung": {
              "ứng dụng/json;odata.metadata=tối thiểu;odata.streaming=đúng": {
                "sơ đồ": {
                  "$ref": "#/thành phần/sơ đồ/IEdmModel"
                }
              },
              "ứng dụng/json;odata.metadata=tối thiểu;odata.streaming=sai": {
                "sơ đồ": {
                  "$ref": "#/thành phần/sơ đồ/IEdmModel"
                }
              },
              "ứng dụng/json;odata.metadata=tối thiểu": {
                "sơ đồ": {
                  "$ref": "#/thành phần/sơ đồ/IEdmModel"
                }
              },
              "ứng dụng/json;odata.metadata=đầy đủ;odata.streaming=đúng": {
                "sơ đồ": {
                  "$ref": "#/thành phần/sơ đồ/IEdmModel"
                }
              },
              "ứng dụng/json;odata.metadata=đầy đủ;odata.streaming=sai": {
                "sơ đồ": {
                  "$ref": "#/thành phần/sơ đồ/IEdmModel"
                }
              },
              "ứng dụng/json;odata.metadata=đầy đủ": {
                "sơ đồ": {
                  "$ref": "#/thành phần/sơ đồ/IEdmModel"
                }
              },
              "ứng dụng/json;odata.metadata=không có;odata.streaming=đúng": {
                "sơ đồ": {
                  "$ref": "#/thành phần/sơ đồ/IEdmModel"
                }
              },
              "ứng dụng/json;odata.metadata=không có;odata.streaming=sai": {
                "sơ đồ": {
                  "$ref": "#/thành phần/sơ đồ/IEdmModel"
                }
              },
              "ứng dụng/json;odata.metadata=không có": {
                "sơ đồ": {
                  "$ref": "#/thành phần/sơ đồ/IEdmModel"
                }
              },
              "ứng dụng/json;odata.streaming=đúng": {
                "sơ đồ": {
                  "$ref": "#/thành phần/sơ đồ/IEdmModel"
                }
              },
              "ứng dụng/json;odata.streaming=sai": {
                "sơ đồ": {
                  "$ref": "#/thành phần/sơ đồ/IEdmModel"
                }
              },
              "ứng dụng/json": {
                "sơ đồ": {
                  "$ref": "#/thành phần/sơ đồ/IEdmModel"
                }
              },
              "ứng dụng/xml": {
                "sơ đồ": {
                  "$ref": "#/thành phần/sơ đồ/IEdmModel"
                }
              },
              "văn bản/thuần túy": {
                "sơ đồ": {
                  "$ref": "#/thành phần/sơ đồ/IEdmModel"
                }
              },
              "ứng dụng/octet-stream": {
                "sơ đồ": {
                  "$ref": "#/thành phần/sơ đồ/IEdmModel"
                }
              },
              "văn bản/json": {
                "sơ đồ": {
                  "$ref": "#/thành phần/sơ đồ/IEdmModel"
                }
              }
            }
          }
        }
      }
    },
    "/$siêu dữ liệu": {
      "lấy": {
        "thẻ": [
          "Siêu dữ liệu"
        ],
        "operationId": "$siêu dữ liệu",
        "phản hồi": {
          "200": {
            "description": "Thành công",
            "nội dung": {
              "ứng dụng/json;odata.metadata=tối thiểu;odata.streaming=đúng": {
                "sơ đồ": {
                  "$ref": "#/thành phần/sơ đồ/IEdmModel"
                }
              },
              "ứng dụng/json;odata.metadata=tối thiểu;odata.streaming=sai": {
                "sơ đồ": {
                  "$ref": "#/thành phần/sơ đồ/IEdmModel"
                }
              },
              "ứng dụng/json;odata.metadata=tối thiểu": {
                "sơ đồ": {
                  "$ref": "#/thành phần/sơ đồ/IEdmModel"
                }
              },
              "ứng dụng/json;odata.metadata=đầy đủ;odata.streaming=đúng": {
                "sơ đồ": {
                  "$ref": "#/thành phần/sơ đồ/IEdmModel"
                }
              },
              "ứng dụng/json;odata.metadata=đầy đủ;odata.streaming=sai": {
                "sơ đồ": {
                  "$ref": "#/thành phần/sơ đồ/IEdmModel"
                }
              },
              "ứng dụng/json;odata.metadata=đầy đủ": {
                "sơ đồ": {
                  "$ref": "#/thành phần/sơ đồ/IEdmModel"
                }
              },
              "ứng dụng/json;odata.metadata=không có;odata.streaming=đúng": {
                "sơ đồ": {
                  "$ref": "#/thành phần/sơ đồ/IEdmModel"
                }
              },
              "ứng dụng/json;odata.metadata=không có;odata.streaming=sai": {
                "sơ đồ": {
                  "$ref": "#/thành phần/sơ đồ/IEdmModel"
                }
              },
              "ứng dụng/json;odata.metadata=không có": {
                "sơ đồ": {
                  "$ref": "#/thành phần/sơ đồ/IEdmModel"
                }
              },
              "ứng dụng/json;odata.streaming=đúng": {
                "sơ đồ": {
                  "$ref": "#/thành phần/sơ đồ/IEdmModel"
                }
              },
              "ứng dụng/json;odata.streaming=sai": {
                "sơ đồ": {
                  "$ref": "#/thành phần/sơ đồ/IEdmModel"
                }
              },
              "ứng dụng/json": {
                "sơ đồ": {
                  "$ref": "#/thành phần/sơ đồ/IEdmModel"
                }
              },
              "ứng dụng/xml": {
                "sơ đồ": {
                  "$ref": "#/thành phần/sơ đồ/IEdmModel"
                }
              },
              "văn bản/thuần túy": {
                "sơ đồ": {
                  "$ref": "#/thành phần/sơ đồ/IEdmModel"
                }
              },
              "ứng dụng/octet-stream": {
                "sơ đồ": {
                  "$ref": "#/thành phần/sơ đồ/IEdmModel"
                }
              },
              "văn bản/json": {
                "sơ đồ": {
                  "$ref": "#/thành phần/sơ đồ/IEdmModel"
                }
              }
            }
          }
        }
      }
    },
    "/.": {
      "lấy": {
        "thẻ": [
          "Siêu dữ liệu"
        ],
        "operationId": "./",
        "phản hồi": {
          "200": {
            "description": "Thành công",
            "nội dung": {
              "ứng dụng/json;odata.metadata=tối thiểu;odata.streaming=đúng": {
                "sơ đồ": {
                  "$ref": "#/components/schemas/ODataServiceDocument"
                }
              },
              "ứng dụng/json;odata.metadata=tối thiểu;odata.streaming=sai": {
                "sơ đồ": {
                  "$ref": "#/components/schemas/ODataServiceDocument"
                }
              },
              "ứng dụng/json;odata.metadata=tối thiểu": {
                "sơ đồ": {
                  "$ref": "#/components/schemas/ODataServiceDocument"
                }
              },
              "ứng dụng/json;odata.metadata=đầy đủ;odata.streaming=đúng": {
                "sơ đồ": {
                  "$ref": "#/components/schemas/ODataServiceDocument"
                }
              },
              "ứng dụng/json;odata.metadata=đầy đủ;odata.streaming=sai": {
                "sơ đồ": {
                  "$ref": "#/components/schemas/ODataServiceDocument"
                }
              },
              "ứng dụng/json;odata.metadata=đầy đủ": {
                "sơ đồ": {
                  "$ref": "#/components/schemas/ODataServiceDocument"
                }
              },
              "ứng dụng/json;odata.metadata=không có;odata.streaming=đúng": {
                "sơ đồ": {
                  "$ref": "#/components/schemas/ODataServiceDocument"
                }
              },
              "ứng dụng/json;odata.metadata=không có;odata.streaming=sai": {
                "sơ đồ": {
                  "$ref": "#/components/schemas/ODataServiceDocument"
                }
              },
              "ứng dụng/json;odata.metadata=không có": {
                "sơ đồ": {
                  "$ref": "#/components/schemas/ODataServiceDocument"
                }
              },
              "ứng dụng/json;odata.streaming=đúng": {
                "sơ đồ": {
                  "$ref": "#/components/schemas/ODataServiceDocument"
                }
              },
              "ứng dụng/json;odata.streaming=sai": {
                "sơ đồ": {
                  "$ref": "#/components/schemas/ODataServiceDocument"
                }
              },
              "ứng dụng/json": {
                "sơ đồ": {
                  "$ref": "#/components/schemas/ODataServiceDocument"
                }
              },
              "ứng dụng/xml": {
                "sơ đồ": {
                  "$ref": "#/components/schemas/ODataServiceDocument"
                }
              },
              "văn bản/thuần túy": {
                "sơ đồ": {
                  "$ref": "#/components/schemas/ODataServiceDocument"
                }
              },
              "ứng dụng/octet-stream": {
                "sơ đồ": {
                  "$ref": "#/components/schemas/ODataServiceDocument"
                }
              },
              "văn bản/json": {
                "sơ đồ": {
                  "$ref": "#/components/schemas/ODataServiceDocument"
                }
              }
            }
          }
        }
      }
    },
    "/": {
      "lấy": {
        "thẻ": [
          "Siêu dữ liệu"
        ],
        "operationId": "",
        "phản hồi": {
          "200": {
            "description": "Thành công",
            "nội dung": {
              "ứng dụng/json;odata.metadata=tối thiểu;odata.streaming=đúng": {
                "sơ đồ": {
                  "$ref": "#/components/schemas/ODataServiceDocument"
                }
              },
              "ứng dụng/json;odata.metadata=tối thiểu;odata.streaming=sai": {
                "sơ đồ": {
                  "$ref": "#/components/schemas/ODataServiceDocument"
                }
              },
              "ứng dụng/json;odata.metadata=tối thiểu": {
                "sơ đồ": {
                  "$ref": "#/components/schemas/ODataServiceDocument"
                }
              },
              "ứng dụng/json;odata.metadata=đầy đủ;odata.streaming=đúng": {
                "sơ đồ": {
                  "$ref": "#/components/schemas/ODataServiceDocument"
                }
              },
              "ứng dụng/json;odata.metadata=đầy đủ;odata.streaming=sai": {
                "sơ đồ": {
                  "$ref": "#/components/schemas/ODataServiceDocument"
                }
              },
              "ứng dụng/json;odata.metadata=đầy đủ": {
                "sơ đồ": {
                  "$ref": "#/components/schemas/ODataServiceDocument"
                }
              },
              "ứng dụng/json;odata.metadata=không có;odata.streaming=đúng": {
                "sơ đồ": {
                  "$ref": "#/components/schemas/ODataServiceDocument"
                }
              },
              "ứng dụng/json;odata.metadata=không có;odata.streaming=sai": {
                "sơ đồ": {
                  "$ref": "#/components/schemas/ODataServiceDocument"
                }
              },
              "ứng dụng/json;odata.metadata=không có": {
                "sơ đồ": {
                  "$ref": "#/components/schemas/ODataServiceDocument"
                }
              },
              "ứng dụng/json;odata.streaming=đúng": {
                "sơ đồ": {
                  "$ref": "#/components/schemas/ODataServiceDocument"
                }
              },
              "ứng dụng/json;odata.streaming=sai": {
                "sơ đồ": {
                  "$ref": "#/components/schemas/ODataServiceDocument"
                }
              },
              "ứng dụng/json": {
                "sơ đồ": {
                  "$ref": "#/components/schemas/ODataServiceDocument"
                }
              },
              "ứng dụng/xml": {
                "sơ đồ": {
                  "$ref": "#/components/schemas/ODataServiceDocument"
                }
              },
              "văn bản/thuần túy": {
                "sơ đồ": {
                  "$ref": "#/components/schemas/ODataServiceDocument"
                }
              },
              "ứng dụng/octet-stream": {
                "sơ đồ": {
                  "$ref": "#/components/schemas/ODataServiceDocument"
                }
              },
              "văn bản/json": {
                "sơ đồ": {
                  "$ref": "#/components/schemas/ODataServiceDocument"
                }
              }
            }
          }
        }
      }
    },
    "/cập nhật": {
      "lấy": {
        "thẻ": [
          "Cập nhật"
        ],
        "summary": "Nhận tất cả các bản tóm tắt cập nhật bảo mật",
        "description": "Lấy danh sách tất cả các bản cập nhật bảo mật của Microsoft. Mỗi bản cập nhật đều bao gồm một liên kết đến thông tin chi tiết về bản cập nhật, được định dạng theo\r\nthe [Common Vulnerability Reporting Framework](https://www.icasi.org/cvrf). Danh sách này có thể được xử lý bằng\r\n[OData URL filtration](https://docs.oasis-open.org/odata/odata/v4.0/errata03/os/complete/part2-url-conventions/odata-v4.0-errata03-os-part2-url-conventions-complete.html#_Toc453752356)\r\nngày phát hành hiện tại và ban đầu.",
        "tham số": [
          {
            "tên": "tùy chọn",
            "trong": "truy vấn",
            "description": "Tùy chọn truy vấn OData",
            "sơ đồ": {
              "$ref": "#/components/schemas/UpdateODataQueryOptions"
            }
          }
        ],
        "phản hồi": {
          "200": {
            "description": "Thành công"
          }
        }
      }
    },
    "/Cập nhật": {
      "lấy": {
        "thẻ": [
          "Cập nhật"
        ],
        "summary": "Nhận tất cả các bản tóm tắt cập nhật bảo mật",
        "description": "Lấy danh sách tất cả các bản cập nhật bảo mật của Microsoft. Mỗi bản cập nhật đều bao gồm một liên kết đến thông tin chi tiết về bản cập nhật, được định dạng theo\r\nthe [Common Vulnerability Reporting Framework](https://www.icasi.org/cvrf). Danh sách này có thể được xử lý bằng\r\n[OData URL filtration](https://docs.oasis-open.org/odata/odata/v4.0/errata03/os/complete/part2-url-conventions/odata-v4.0-errata03-os-part2-url-conventions-complete.html#_Toc453752356)\r\nngày phát hành hiện tại và ban đầu.",
        "operationId": "Cập nhật",
        "tham số": [
          {
            "tên": "tùy chọn",
            "trong": "truy vấn",
            "description": "Tùy chọn truy vấn OData",
            "sơ đồ": {
              "$ref": "#/components/schemas/UpdateODataQueryOptions"
            }
          }
        ],
        "phản hồi": {
          "200": {
            "description": "Thành công"
          }
        }
      }
    },
    "/Cập nhật/$count": {
      "lấy": {
        "thẻ": [
          "Cập nhật"
        ],
        "summary": "Nhận tất cả các bản tóm tắt cập nhật bảo mật",
        "description": "Lấy danh sách tất cả các bản cập nhật bảo mật của Microsoft. Mỗi bản cập nhật đều bao gồm một liên kết đến thông tin chi tiết về bản cập nhật, được định dạng theo\r\nthe [Common Vulnerability Reporting Framework](https://www.icasi.org/cvrf). Danh sách này có thể được xử lý bằng\r\n[OData URL filtration](https://docs.oasis-open.org/odata/odata/v4.0/errata03/os/complete/part2-url-conventions/odata-v4.0-errata03-os-part2-url-conventions-complete.html#_Toc453752356)\r\nngày phát hành hiện tại và ban đầu.",
        "operationId": "Cập nhật/$count",
        "tham số": [
          {
            "tên": "tùy chọn",
            "trong": "truy vấn",
            "description": "Tùy chọn truy vấn OData",
            "sơ đồ": {
              "$ref": "#/components/schemas/UpdateODataQueryOptions"
            }
          }
        ],
        "phản hồi": {
          "200": {
            "description": "Thành công"
          }
        }
      }
    },
    "/cập nhật({khóa})": {
      "lấy": {
        "thẻ": [
          "Cập nhật"
        ],
        "summary": "Nhận tóm tắt cập nhật bảo mật theo khóa",
        "description": "Lấy danh sách các bản cập nhật bảo mật của Microsoft theo ID bản cập nhật, ID lỗ hổng ([CVE](https://cve.mitre.org/about)) hoặc\r\nnăm. Mỗi bản cập nhật đều bao gồm một liên kết đến thông tin chi tiết về bản cập nhật, được định dạng theo [Common Vulnerability Reporting\r\nFramework](https://www.icasi.org/cvrf). Có thể thao tác danh sách này bằng\r\n[lọc URL OData](https://docs.oasis-open.org/odata/odata/v4.0/errata03/os/complete/part2-url-conventions/odata-v4.0-errata03-os-part2-url-conventions-complete.html#_Toc453752356)\r\nngày phát hành hiện tại và ban đầu.",
        "tham số": [
          {
            "tên": "khóa",
            "trong": "truy vấn",
            "description": "ID cập nhật (yyyy-mmm), ID lỗ hổng (số CVE) hoặc năm (yyyy)",
            "sơ đồ": {
              "kiểu": "chuỗi"
            }
          },
          {
            "tên": "tùy chọn",
            "trong": "truy vấn",
            "description": "Tùy chọn truy vấn OData",
            "sơ đồ": {
              "$ref": "#/components/schemas/UpdateODataQueryOptions"
            }
          }
        ],
        "phản hồi": {
          "200": {
            "description": "Thành công"
          }
        }
      }
    },
    "/cập nhật
