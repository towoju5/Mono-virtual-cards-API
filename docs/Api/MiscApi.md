# Towoju5\MonoCards\MiscApi

All URIs are relative to *https://api.withmono.com/issuing/v1/cards*

Method | HTTP request | Description
------------- | ------------- | -------------
[**createaVirtualCard**](MiscApi.md#createavirtualcard) | **POST** /virtual | Create a Virtual Card
[**fetchCardDetails**](MiscApi.md#fetchcarddetails) | **GET** /61bb3a0d5f53902db40eb478 | Fetch Card Details
[**fetchCardTransactions**](MiscApi.md#fetchcardtransactions) | **GET** /61bb3a0d5f53902db40eb478/transactions | Fetch Card Transactions
[**freezeaCard**](MiscApi.md#freezeacard) | **PATCH** /61bb3a0d5f53902db40eb478/freeze | Freeze a Card
[**fundaVirtualCard**](MiscApi.md#fundavirtualcard) | **POST** /61bb3a0d5f53902db40eb478/fund | Fund a Virtual Card
[**liquidateCardBalance**](MiscApi.md#liquidatecardbalance) | **PATCH** /61bb3a0d5f53902db40eb478/liquidate | Liquidate Card Balance
[**unfreezeaCard**](MiscApi.md#unfreezeacard) | **PATCH** /61bb3a0d5f53902db40eb478/unfreeze | Unfreeze a Card
[**updateCardPin**](MiscApi.md#updatecardpin) | **PATCH** /61bb3a0d5f53902db40eb478/pin | Update Card Pin

# **createaVirtualCard**
> createaVirtualCard($body)

Create a Virtual Card

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');
// Configure API key authorization: apiKey
$config = Towoju5\MonoCards\Configuration::getDefaultConfiguration()->setApiKey('mono-sec-key', 'YOUR_API_KEY');
// Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
// $config = Towoju5\MonoCards\Configuration::getDefaultConfiguration()->setApiKeyPrefix('mono-sec-key', 'Bearer');

$apiInstance = new Towoju5\MonoCards\Api\MiscApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client(),
    $config
);
$body = new \Towoju5\MonoCards\Model\null(); //  | 

try {
    $apiInstance->createaVirtualCard($body);
} catch (Exception $e) {
    echo 'Exception when calling MiscApi->createaVirtualCard: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **body** | [****](../Model/.md)|  |

### Return type

void (empty response body)

### Authorization

[apiKey](../../README.md#apiKey)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **fetchCardDetails**
> fetchCardDetails()

Fetch Card Details

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');
// Configure API key authorization: apiKey
$config = Towoju5\MonoCards\Configuration::getDefaultConfiguration()->setApiKey('mono-sec-key', 'YOUR_API_KEY');
// Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
// $config = Towoju5\MonoCards\Configuration::getDefaultConfiguration()->setApiKeyPrefix('mono-sec-key', 'Bearer');

$apiInstance = new Towoju5\MonoCards\Api\MiscApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client(),
    $config
);

try {
    $apiInstance->fetchCardDetails();
} catch (Exception $e) {
    echo 'Exception when calling MiscApi->fetchCardDetails: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters
This endpoint does not need any parameter.

### Return type

void (empty response body)

### Authorization

[apiKey](../../README.md#apiKey)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **fetchCardTransactions**
> fetchCardTransactions()

Fetch Card Transactions

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');
// Configure API key authorization: apiKey
$config = Towoju5\MonoCards\Configuration::getDefaultConfiguration()->setApiKey('mono-sec-key', 'YOUR_API_KEY');
// Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
// $config = Towoju5\MonoCards\Configuration::getDefaultConfiguration()->setApiKeyPrefix('mono-sec-key', 'Bearer');

$apiInstance = new Towoju5\MonoCards\Api\MiscApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client(),
    $config
);

try {
    $apiInstance->fetchCardTransactions();
} catch (Exception $e) {
    echo 'Exception when calling MiscApi->fetchCardTransactions: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters
This endpoint does not need any parameter.

### Return type

void (empty response body)

### Authorization

[apiKey](../../README.md#apiKey)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **freezeaCard**
> freezeaCard()

Freeze a Card

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');
// Configure API key authorization: apiKey
$config = Towoju5\MonoCards\Configuration::getDefaultConfiguration()->setApiKey('mono-sec-key', 'YOUR_API_KEY');
// Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
// $config = Towoju5\MonoCards\Configuration::getDefaultConfiguration()->setApiKeyPrefix('mono-sec-key', 'Bearer');

$apiInstance = new Towoju5\MonoCards\Api\MiscApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client(),
    $config
);

try {
    $apiInstance->freezeaCard();
} catch (Exception $e) {
    echo 'Exception when calling MiscApi->freezeaCard: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters
This endpoint does not need any parameter.

### Return type

void (empty response body)

### Authorization

[apiKey](../../README.md#apiKey)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **fundaVirtualCard**
> fundaVirtualCard($body)

Fund a Virtual Card

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');
// Configure API key authorization: apiKey
$config = Towoju5\MonoCards\Configuration::getDefaultConfiguration()->setApiKey('mono-sec-key', 'YOUR_API_KEY');
// Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
// $config = Towoju5\MonoCards\Configuration::getDefaultConfiguration()->setApiKeyPrefix('mono-sec-key', 'Bearer');

$apiInstance = new Towoju5\MonoCards\Api\MiscApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client(),
    $config
);
$body = new \Towoju5\MonoCards\Model\null(); //  | 

try {
    $apiInstance->fundaVirtualCard($body);
} catch (Exception $e) {
    echo 'Exception when calling MiscApi->fundaVirtualCard: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **body** | [****](../Model/.md)|  |

### Return type

void (empty response body)

### Authorization

[apiKey](../../README.md#apiKey)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **liquidateCardBalance**
> liquidateCardBalance($body)

Liquidate Card Balance

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');
// Configure API key authorization: apiKey
$config = Towoju5\MonoCards\Configuration::getDefaultConfiguration()->setApiKey('mono-sec-key', 'YOUR_API_KEY');
// Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
// $config = Towoju5\MonoCards\Configuration::getDefaultConfiguration()->setApiKeyPrefix('mono-sec-key', 'Bearer');

$apiInstance = new Towoju5\MonoCards\Api\MiscApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client(),
    $config
);
$body = new \Towoju5\MonoCards\Model\null(); //  | 

try {
    $apiInstance->liquidateCardBalance($body);
} catch (Exception $e) {
    echo 'Exception when calling MiscApi->liquidateCardBalance: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **body** | [****](../Model/.md)|  |

### Return type

void (empty response body)

### Authorization

[apiKey](../../README.md#apiKey)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **unfreezeaCard**
> unfreezeaCard()

Unfreeze a Card

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');
// Configure API key authorization: apiKey
$config = Towoju5\MonoCards\Configuration::getDefaultConfiguration()->setApiKey('mono-sec-key', 'YOUR_API_KEY');
// Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
// $config = Towoju5\MonoCards\Configuration::getDefaultConfiguration()->setApiKeyPrefix('mono-sec-key', 'Bearer');

$apiInstance = new Towoju5\MonoCards\Api\MiscApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client(),
    $config
);

try {
    $apiInstance->unfreezeaCard();
} catch (Exception $e) {
    echo 'Exception when calling MiscApi->unfreezeaCard: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters
This endpoint does not need any parameter.

### Return type

void (empty response body)

### Authorization

[apiKey](../../README.md#apiKey)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **updateCardPin**
> updateCardPin($body)

Update Card Pin

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');
// Configure API key authorization: apiKey
$config = Towoju5\MonoCards\Configuration::getDefaultConfiguration()->setApiKey('mono-sec-key', 'YOUR_API_KEY');
// Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
// $config = Towoju5\MonoCards\Configuration::getDefaultConfiguration()->setApiKeyPrefix('mono-sec-key', 'Bearer');

$apiInstance = new Towoju5\MonoCards\Api\MiscApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client(),
    $config
);
$body = new \Towoju5\MonoCards\Model\null(); //  | 

try {
    $apiInstance->updateCardPin($body);
} catch (Exception $e) {
    echo 'Exception when calling MiscApi->updateCardPin: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **body** | [****](../Model/.md)|  |

### Return type

void (empty response body)

### Authorization

[apiKey](../../README.md#apiKey)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

